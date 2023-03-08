<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Responsive Bootstrap Web Design</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>
	<h1>Responsive Bootstrap Web Design</h1>
	<p>Created by: <strong>Hasan ÇELİK</strong></p>
	<p>If you are looking to create a responsive web design using Bootstrap, you have come to the right place. Bootstrap is a powerful front-end framework that allows you to create beautiful and responsive websites quickly and easily.</p>
	<p>Bootstrap is based on HTML5 and CSS3, which means that you have access to all the latest features and technologies. With Bootstrap, you can create websites that look great on all devices, from desktops to smartphones.</p>
	<h2>Getting Started</h2>
	<p>To get started with Bootstrap, you need to download the framework from the official website. Once you have downloaded Bootstrap, you can include it in your project by adding the following code to the <code>&lt;head&gt;</code> section of your HTML file:</p>
	<pre>
		<code>&lt;link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"&gt;</code>
	</pre>
	<p>You also need to include jQuery and Bootstrap JavaScript files, like this:</p>
	<pre>
		<code>&lt;script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"&gt;&lt;/script&gt;</code>
		<code>&lt;script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"&gt;&lt;/script&gt;</code>
	</pre>
	<h2>Creating a Responsive Layout</h2>
	<p>Bootstrap provides a grid system that allows you to create responsive layouts. The grid system is based on a 12-column layout, which you can customize to suit your needs. To create a responsive layout, you need to include the following code in your HTML file:</p>
	<pre>
		<code>&lt;div class="container"&gt;</code>
		<code>  &lt;div class="row"&gt;</code>
		<code>    &lt;div class="col-sm-4"&gt;</code>
		<code>      &lt;p&gt;Column 1&lt;/p&gt;</code>
		<code>    &lt;/div&gt;</code>
		<code>    &lt;div class="col-sm-4"&gt;</code>
		<code>      &lt;p&gt;Column 2&lt;/p&gt;</code>
		<code>    &lt;/div&gt;</code>
		<code>    &lt;div class="col-sm-4"&gt;</code>
		<code>      &lt;p&gt;Column 3&lt;/p&gt;</code>
		<code>    &lt;/div&gt;</code>
		<code>  &lt;/div&gt;</code>
		<code>&lt;/div&gt;</code>
	</pre>
	<p>In this example, we have created three columns that will each take up 4 of the 12 available columns on small and
