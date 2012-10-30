---
layout: post
title: "A First Test"
date: 2012-10-29 18:42
comments: true
categories: 
---
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% codeblock lang:ruby %}
class Fixnum
  def prime?
    ('1' * self) !~ /^1?$|^(11+?)\1+$/
  end
end
{% endcodeblock %}
<!-- more -->

Some more codeblock tests follow:

## Ruby

{% codeblock lang:ruby %}
class Fixnum
  def prime?
    ('1' * self) !~ /^1?$|^(11+?)\1+$/
  end
end
{% endcodeblock %}


## Shell

{% codeblock lang:sh %}
## Commiting: Site updated at 2012-10-30 10:23:14 UTC
[master 304fd42] Site updated at 2012-10-30 10:23:14 UTC
 5 files changed, 27 insertions(+), 24 deletions(-)

## Pushing generated _deploy website
Username for 'https://github.com': muellerj
Password for 'https://muellerj@github.com':
Counting objects: 27, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (10/10), done.
Writing objects: 100% (14/14), 1.54 KiB, done.
Total 14 (delta 6), reused 0 (delta 0)
To https://github.com/muellerj/muellerj.github.com
   9b7963f..304fd42  master -> master

## Github Pages deploy complete
cd -

C:\Users\muellerj\Sandbox\octopress>
{% endcodeblock %}


## Matlab

{% codeblock lang:matlab %}
% Show debugging plot if requested
if nargin > 1 && strcmp(varargin{:}, 'verbose')
  figure; hold on; grid on;
  x = 0:0.01:1;
  plot(x, 0.5*x, ustyle, 'Color', ucolour, 'LineWidth', 2);
  plot(x, 1.0*x, ostyle, 'Color', ocolour, 'LineWidth', 2);
  plot(x, 2.0*x, nstyle, 'Color', ncolour, 'LineWidth', 2);
  legend('understeering', 'oversteering', 'neutral')
  colour = ncolour; style = nstyle; return
end
{% endcodeblock %}


## LaTeX

{% codeblock lang:latex %}
% PhD thesis Jonas Mueller
% created on 2008-05-12.
\documentclass[a4paper, 12pt]{book}

% Define readiness for submission 
% (1 = draft, 2 = final draft, 3 = submission document)
\newcounter{draftlevel}
\setcounter{draftlevel}{3}

\usepackage{./framework/mainstyle}

\begin{document}

  \frontmatter
    \input{./framework/fancy_front.sty}
    \input{./tex/frontmatter/titlepage.tex}
    \blankpage
{% endcodeblock %}