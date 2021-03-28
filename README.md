# Atom-school-html-project
<!DOCTYPE html>
<html lang="en-US">
<head>
	<meta charset="utf-8">
	<meta name="author" content="Dr. Eleanor Gaye">
	<link rel="stylesheet" href="style.css">
	<title>Marking Up a Letter Assignment</title>
  <style>
      body {
        max-width: 800px;
        margin: 0 auto;
      }

      .sender-column {
        text-align: right;
      }

      h1 {
        font-size: 1.5em;
      }

      h2 {
        font-size: 1.3em;
      }

      p,ul,ol,dl,address {
        font-size: 1.1em;
      }

      p, li, dd, dt, address {
        line-height: 1.5;
      }
    </style>
  </head>
  <body>

	<p class="sender-column">
	<strong>Dr. Eleanor Gaye</strong><br>
	Awesome Science faculty<br>
	University of Awesome<br>
	Bobtown, CA 99999,<br>
	USA<br>
	<strong>Tel</strong>: 123-456-7890<br>
	<strong>Email</strong>: no_reply@example.com
	</p>

	<p class="sender-column">
	<time datetime="2016-01-20">20 January 2016</time>
	</p>
  <p>
  	<strong>Miss Eileen Dover</strong><br>
  	4321 Cliff Top Edge<br>
  	Dover, CT9 XXX<br>
  	UK
  	</p>

  	<h1>
  	Re: Eileen Dover university application
  	</h1>

  	<p>
  	Dear Eileen,
  	</p>

  	<p>
  	Thank you for your recent application to join us at the University of Awesome's science faculty to study as part of your <em><abbr title="Doctor of Philosophy">PhD</abbr></em> next year. I will answer your questions one by one, in the following sections.
  	</p>

  	<h2>Starting dates</h2>

  	<p>
  	We are happy to accomodate you starting your study with us at any time, however it would suit us better if you could start at the beginning of a semester; the start dates for each one are as follows:
  	</p>

  	<ul>
  	<li>First semester: <time datetime="2016-09-09">9 September 2016</time></li>
  	<li>Second semester: <time datetime="2017-01-15">15 January 2017</time></li>
  	<li>Third semester: <time datetime="2017-05-02">2 May 2017</time></li>
  	</ul>
