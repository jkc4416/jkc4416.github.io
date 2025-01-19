---
layout: post
title: "Building Data Pipelines for Automated Model Management: Why Is It Necessary?"
# subtitle: 
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
tags: [MLOps, Data Pipeline, Automated Model Management, Machine Learning Operations, Continuous Training (CT), Model Registry, Feature Store, Data Automation, CI/CD Pipelines, Data Engineering, Model Monitoring, Data Drift, Cloud-Native Solutions, Explainable AI (XAI), Infrastructure as Code (IaC), Low-code/No-code ML Tools, AI Scalability, ML Workflow Automation, End-to-End AI Systems, Observability in AI]
comments: true
mathjax: true
author: Kyungchae Jung
---

{: .box-success}
**Have you ever faced situations like these?**<br>
“I trained and deployed a model, but a week later, the data changed, and the performance dropped significantly.”<br>“I developed a new model version, but I can’t trace which data was used, how it was trained, or even under what conditions and by whom.”<br>“I’m familiar with CI/CD pipelines, so why is updating ML models so complicated?”

**The key to solving these operational challenges in managing machine learning models lies in building data pipelines and automated model management. Automating the end-to-end process—from periodic data collection and preprocessing, feature engineering, model training and validation, to deploying new model versions—makes AI projects significantly more robust.**<br><br>

## 1. What is a Data Pipeline?

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
