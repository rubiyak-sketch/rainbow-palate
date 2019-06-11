# rainbow-palate
Everything around you is colorful,
Just Paint your imagination on paper
<!DOCTYPE HTML>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>
    
      Understanding the GitHub flow &middot; GitHub Guides
    
  </title>
  <link rel="icon" type="image/x-icon" href="/favicon.ico">

  <meta name="viewport" content="width=device-width,initial-scale=1">

  <link rel="stylesheet" href="/components/gridism/gridism.css">
  <link rel="stylesheet" href="/components/primer/markdown.css">
  <link rel="stylesheet" href="/components/primer/octicons.css">
  <link href="/stylesheets/main.css" rel="stylesheet" />
  <link href="/stylesheets/pygments.css" rel="stylesheet" />

  <script src="/javascripts/jquery.js" type="text/javascript"></script>
  <script src="/javascripts/snap.svg-min.js" type="text/javascript"></script>
  <script src="/javascripts/application.js" type="text/javascript"></script>

  <script type="text/javascript">
    var _gaq = _gaq || [];
    _gaq.push(['_setAccount', 'UA-3769691-29']);
    _gaq.push(['_trackPageview']);
    (function() {
      var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
      ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
    })();
  </script>

</head>
<body>

  <header>
    <div class="wrap">
      <ul class="links">
        <li><a href="https://www.youtube.com/githubguides">Video Guides</a></li>
        <li><a href="https://help.github.com">GitHub Help</a></li>
        <li class="nav-github"><a href="https://github.com">GitHub.com</a></li>
        <li class="nav-rss"><a href="/feed/index.xml"><span class="octicon octicon-rss"></span></a></li>
      </ul>

      <a href ="/"><img src="/images/logo@2x.png" width="136" height="25" alt ="GitHub Guides logo"/></a>
    </div>
  </header>

  <article class="full">
  <div class="article-heading js-article-heading js-geopattern" style="background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMDAiIGhlaWdodD0iODY0Ij48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSJyZ2IoMTQ3LCA0NSwgMTEyKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4xMDY2NjY2NjY2NjY2NjY2NztzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgLTg3LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjEwNjY2NjY2NjY2NjY2NjY3O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA3NzcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDcyMDAwMDAwMDAwMDAwMDE7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIC02My4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4wNzIwMDAwMDAwMDAwMDAwMTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgODAxLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjEyNDAwMDAwMDAwMDAwMDAxO3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAtMzkuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMTI0MDAwMDAwMDAwMDAwMDE7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDgyNS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgLTE1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjExNTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA4NDkuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDU0NjY2NjY2NjY2NjY2Njc7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDkuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDU0NjY2NjY2NjY2NjY2Njc7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDg3My4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wNjMzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMzMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDYzMzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDg5Ny4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4wMjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNTcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDI7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDkyMS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wMjg2NjY2NjY2NjY2NjY2Njc7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDgxLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjAyODY2NjY2NjY2NjY2NjY2NztzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgOTQ1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjExNTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMDUuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTE1MzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDk2OS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTI5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjExNTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA5OTMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDQ2O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxNTMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDQ2O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMDE3LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjAzNzMzMzMzMzMzMzMzMzMzO3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxNzcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDM3MzMzMzMzMzMzMzMzMzM7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDEwNDEuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTE1MzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDIwMS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTA2NS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMzI2NjY2NjY2NjY2NjY2NTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMjI1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjEzMjY2NjY2NjY2NjY2NjY1O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMDg5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjE0MTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAyNDkuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMTQxMzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDExMTMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDk4O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAyNzMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDk4O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMTM3LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjA3MjAwMDAwMDAwMDAwMDAxO3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAyOTcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDcyMDAwMDAwMDAwMDAwMDE7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDExNjEuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMTI0MDAwMDAwMDAwMDAwMDE7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDMyMS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4xMjQwMDAwMDAwMDAwMDAwMTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTE4NS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4wNTQ2NjY2NjY2NjY2NjY2NztzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMzQ1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjA1NDY2NjY2NjY2NjY2NjY3O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMjA5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjA0NjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMzY5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjA0NjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTIzMy4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wOTg7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDM5My4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wOTg7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDEyNTcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTMyNjY2NjY2NjY2NjY2NjU7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDQxNy4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMzI2NjY2NjY2NjY2NjY2NTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTI4MS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wOTg7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDQ0MS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wOTg7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDEzMDUuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTMyNjY2NjY2NjY2NjY2NjU7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDQ2NS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMzI2NjY2NjY2NjY2NjY2NTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTMyOS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4xNDEzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNDg5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjE0MTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxMzUzLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjAyO3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA1MTMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiNkZGQiIHN0eWxlPSJvcGFjaXR5OjAuMDI7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDEzNzcuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTE1MzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDUzNy4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTQwMS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4wNTQ2NjY2NjY2NjY2NjY2NztzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNTYxLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjA1NDY2NjY2NjY2NjY2NjY3O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxNDI1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjA0NjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNTg1LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjA0NjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTQ0OS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wNDY7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDYwOS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4wNDY7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDE0NzMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTE1MzMzMzMzMzMzMzMzMzQ7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDYzMy4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTQ5Ny4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2RkZCIgc3R5bGU9Im9wYWNpdHk6MC4wMjtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNjU3LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZGRkIiBzdHlsZT0ib3BhY2l0eTowLjAyO3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxNTIxLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjA4MDY2NjY2NjY2NjY2NjY2O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA2ODEuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMDgwNjY2NjY2NjY2NjY2NjY7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDE1NDUuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTU7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDcwNS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xNTtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgMTU2OS4wKSIgIC8+PHBhdGggZD0iTTAgNTggQyA1Mi41IDAsIDk3LjUgMCwgMTUwIDU4IFMgMjQ3LjUgMTE2LCAzMDAgNTggUyAzOTcuNSAwLCA0NTAuMCwgNTgiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzIyMiIgc3R5bGU9Im9wYWNpdHk6MC4xMTUzMzMzMzMzMzMzMzMzNDtzdHJva2Utd2lkdGg6MjRweDsiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC03NSwgNzI5LjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjExNTMzMzMzMzMzMzMzMzM0O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCAxNTkzLjApIiAgLz48cGF0aCBkPSJNMCA1OCBDIDUyLjUgMCwgOTcuNSAwLCAxNTAgNTggUyAyNDcuNSAxMTYsIDMwMCA1OCBTIDM5Ny41IDAsIDQ1MC4wLCA1OCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMjIyIiBzdHlsZT0ib3BhY2l0eTowLjEzMjY2NjY2NjY2NjY2NjY1O3N0cm9rZS13aWR0aDoyNHB4OyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTc1LCA3NTMuMCkiICAvPjxwYXRoIGQ9Ik0wIDU4IEMgNTIuNSAwLCA5Ny41IDAsIDE1MCA1OCBTIDI0Ny41IDExNiwgMzAwIDU4IFMgMzk3LjUgMCwgNDUwLjAsIDU4IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMjIiIHN0eWxlPSJvcGFjaXR5OjAuMTMyNjY2NjY2NjY2NjY2NjU7c3Ryb2tlLXdpZHRoOjI0cHg7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtNzUsIDE2MTcuMCkiICAvPjwvc3ZnPg==);">
    <div class="wrap">
      <div class="icon-container">
        <span class="mega-octicon octicon-git-branch"></span>
      </div>
      <h1>Understanding the GitHub flow</h1>
      <span class="article-read-time article-meta">
        <span class="octicon octicon-clock"></span> 5 minute read
      </span>
      
      <a class="article-pdf article-meta" href="/pdfs/githubflow-online.pdf" onClick="_gaq.push(['_trackEvent', 'PDF Download', 'Click', 'githubflow-online.pdf']);">
        <span class="octicon octicon-cloud-download"></span> Download PDF version
      </a>
      
    </div>
  </div>


  <div class="wrap">
    

    <div class="markdown-body content-body full-width">
      <p>GitHub flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly. This guide explains how and why GitHub flow works.</p>

<script type="text/javascript" src="flow.js"></script>

<link rel="stylesheet" type="text/css" href="flow.css" />

<div class="scrollable-diagram js-scrollable-diagram">
  <div class="features-branch-diagram" id="js-features-branch-diagram">
    <svg width="930px" height="350" id="js-features-branch-diagram-svg" xmlns="http://www.w3.org/2000/svg">
      <path d="M66.2711864,5.96363636 C135.523206,5.96363636 143.460673,112 191.02837,112 C238.596067,112 681.049887,112 725.83852,112 C770.627152,112 786.056674,5.95721244 855.110732,5.96363636" id="js-branch-diagram-branch" stroke="#4182C4" stroke-width="4" fill="none"></path>
      <path d="M0,7 L766,7 L920,7" id="js-branch-diagram-master" stroke="#c6d9ed" stroke-width="8"></path>
      <path id="js-branch-diagram-arrow" d="M907.2,10 C910.98,8.95 915.22,8.05 918,7 C914.22,5.95 910.98,5.05 907.2,4" stroke="#c6d9ed" stroke-width="8" fill="none"></path>
    </svg>

    <div class="diagram-icon js-diagram-icon diagram-icon-branch" data-diagram-step="branch">
      <span class="mega-octicon octicon-git-branch"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-1" data-diagram-step="commits">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-2" data-diagram-step="commits">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-3" data-diagram-step="commits">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon js-diagram-icon diagram-icon-pr" data-diagram-step="pr">
      <span class="mega-octicon octicon-git-pull-request"></span>
    </div>
    <div class="diagram-icon js-diagram-icon diagram-icon-merge" data-diagram-step="merge">
      <span class="mega-octicon octicon-git-merge"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-discussion-1" data-diagram-step="code-review">
      <span class="mega-octicon octicon-comment-discussion"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-4" data-diagram-step="code-review">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-discussion-2" data-diagram-step="code-review">
      <span class="mega-octicon octicon-comment-discussion"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-5" data-diagram-step="code-review">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-discussion-3" data-diagram-step="code-review">
      <span class="mega-octicon octicon-comment-discussion"></span>
    </div>
    <div class="diagram-icon-small js-diagram-icon-small diagram-icon-commit-6" data-diagram-step="code-review">
      <span class="mega-octicon octicon-git-commit"></span>
    </div>
    <div class="diagram-icon js-diagram-icon-small diagram-icon-deploy" data-diagram-step="deploy">
      <span class="mega-octicon octicon-squirrel"></span>
    </div>
  </div>
</div>

<div class="flow-content">

  <div class="panel-content js-panel-content js-panel-content-branch" data-step="branch">
    <h3>Create a branch</h3>

    <p>When you're working on a project, you're going to have a bunch of different features or ideas in progress at any given time – some of which are ready to go, and others which are not. Branching exists to help you manage this workflow.</p>

    <p>When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the <code>master</code> branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.</p>

    <h4>ProTip</h4>

    <p>Branching is a core concept in Git, and the entire GitHub flow is based upon it. There's only one rule: anything in the <code>master</code> branch is always deployable.</p>

    <p>Because of this, it's extremely important that your new branch is created off of master when working on a feature or a fix. Your branch name should be descriptive (e.g., <code>refactor-authentication</code>, <code>user-content-cache-key</code>, <code>make-retina-avatars</code>), so that others can see what is being worked on.</p>

  </div>

  <div class="panel-content js-panel-content js-panel-content-commits" data-step="commits">
    <h3>Add commits</h3>

    <p>Once your branch has been created, it's time to start making changes. Whenever you add, edit, or delete a file, you're making a commit, and adding them to your branch. This process of adding commits keeps track of your progress as you work on a feature branch.</p>

    <p>Commits also create a transparent history of your work that others can follow to understand what you've done and why. Each commit has an associated commit message, which is a description explaining why a particular change was made. Furthermore, each commit is considered a separate unit of change. This lets you roll back changes if a bug is found, or if you decide to head in a different direction.</p>

    <h4>ProTip</h4>

    <p>Commit messages are important, especially since Git tracks your changes and then displays them as commits once they're pushed to the server. By writing clear commit messages, you can make it easier for other people to follow along and provide feedback.</p>

  </div>

  <div class="panel-content js-panel-content js-panel-content-pr" data-step="pr">
    <h3>Open a Pull Request</h3>

    <p>Pull Requests initiate discussion about your commits. Because they're tightly integrated with the underlying Git repository, anyone can see exactly what changes would be merged if they accept your request.</p>

    <p>You can open a Pull Request at any point during the development process: when you have little or no code but want to share some screenshots or general ideas, when you're stuck and need help or advice, or when you're ready for someone to review your work. By using GitHub's @mention system in your Pull Request message, you can ask for feedback from specific people or teams, whether they're down the hall or ten time zones away.</p>

    <h4>ProTip</h4>

    <p>Pull Requests are useful for contributing to open source projects and for managing changes to shared repositories. If you're using a Fork &amp; Pull Model, Pull Requests provide a way to notify project maintainers about the changes you'd like them to consider. If you're using a Shared Repository Model, Pull Requests help start code review and conversation about proposed changes before they're merged into the master branch.</p>

  </div>

  <div class="panel-content js-panel-content js-panel-content-code-review" data-step="code-review">

    <h3>Discuss and review your code</h3>

    <p>Once a Pull Request has been opened, the person or team reviewing your changes may have questions or comments. Perhaps the coding style doesn't match project guidelines, the change is missing unit tests, or maybe everything looks great and props are in order. Pull Requests are designed to encourage and capture this type of conversation.</p>

    <p>You can also continue to push to your branch in light of discussion and feedback about your commits. If someone comments that you forgot to do something or if there is a bug in the code, you can fix it in your branch and push up the change. GitHub will show your new commits and any additional feedback you may receive in the unified Pull Request view.</p>

    <h4>ProTip</h4>

    <p>Pull Request comments are written in Markdown, so you can embed images and emoji, use pre-formatted text blocks, and other lightweight formatting.</p>

  </div>

  <div class="panel-content js-panel-content js-panel-content-deploy" data-step="deploy">

    <h3>Deploy</h3>

    <p>With GitHub, you can deploy from a branch for final testing in production before merging to master.</p>

    <p>Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production. If your branch causes issues, you can roll it back by deploying the existing master into production.</p>
  </div>

  <div class="panel-content js-panel-content js-panel-content-merge" data-step="merge">

    <h3>Merge</h3>

    <p>Now that your changes have been verified in production, it is time to merge your code into the master branch.</p>

    <p>Once merged, Pull Requests preserve a record of the historical changes to your code. Because they're searchable, they let anyone go back in time to understand why and how a decision was made.</p>

    <h4>ProTip</h4>

    <p>By incorporating certain keywords into the text of your Pull Request, you can associate issues with code. When your Pull Request is merged, the related issues are also closed. For example, entering the phrase <code>Closes #32</code> would close issue number 32 in the repository. For more information, check out our <a href="https://help.github.com/articles/closing-issues-via-commit-messages">help article</a>.</p>

  </div>

  <a href="#" class="panel-nav prev js-panel-nav-prev" title="Previous" data-proofer-ignore="">
    <span class="mega-octicon octicon-chevron-left"></span>
  </a>

  <a href="#" class="panel-nav next js-panel-nav-next" title="Next" data-proofer-ignore="">
    <span class="mega-octicon octicon-chevron-right"></span>
  </a>


</div>


      <p class="last-updated">Last updated Nov 30, 2017</p>
    </div>
  </div>
</article>


  <footer>
    <div class="wrap">
      <span class="mega-octicon octicon-mark-github"></span>
      <p>
        <a href="https://github.com">GitHub</a> is the best way to build and ship software.<br />
        Powerful collaboration, code review, and code management for open source and private projects.
      </p>
    </div>
  </footer>

</body>
</html>
