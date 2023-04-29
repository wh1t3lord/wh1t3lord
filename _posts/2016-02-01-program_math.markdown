---
layout: "post"
title: "Test js integration"
subtitle: "A test post for JS integration"
active: "journal"
image:
  feature: "pc007.jpg"
date: "2016-02-01"
header-img: "img/postcover/pc007.jpg"
comments: "true"
---


<html class="no-js" lang="en">
<head>
	<meta content="charset=utf-8">
</head>

    <body>

<section id="content" role="main">
		<div class="wrapper">
	<br><br>
			<h2>{{page.title}}</h2>

<p>
  Here I write some text before inserting programming code listing
</p>

{% highlight c++ %}#include <iostream> 

int main()
{
	return 0;
}
{% endhighlight %}

<p>
  $$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$
</p>

<p>
	some JSXGraph integration
</p>

<div id="jxgbox" class="jxgbox" style="width:500px; height:200px;"></div>
<script type="text/javascript">
 var board = JXG.JSXGraph.initBoard('jxgbox', {boundingbox: [-5, 2, 5, -2]});
 var p = board.create('point',[-3,1]);
</script>