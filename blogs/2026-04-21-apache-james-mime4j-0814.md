---
title: "Apache James MIME4J 0.8.14"
url: "http://james.apache.org/james/update/2026/04/21/mime4j-0.8.14.html"
date: "Tue, 21 Apr 2026 03:16:30 +0200"
author: ""
feed_url: "https://james.apache.org/feed"
---
<p>The Apache James developers are pleased to announce the 0.8.14 release of the MIME4J library.</p>

<p>Early adopters can <a href="https://james.apache.org/download.cgi#Apache_Mime4J">download it</a>, any issue can be reported on our issue <a href="https://issues.apache.org/jira/browse/MIME4J">tracker</a>.</p>

<p>The full changes included in this release can be seen in the <a href="https://github.com/apache/james-mime4j/blob/master/CHANGELOG.md">CHANGELOG</a>.</p>

<p>This release adds the following features:</p>

<ul>
  <li>[PERF] Reduce String allocs in RawFieldParser</li>
  <li>[PERF] String allocation &amp; conversions</li>
  <li>[PERF] Boundary matching - prevent QS table rebuilt every call￼</li>
  <li>Adopt JDK 11 as a build target</li>
  <li>MIME4J-333 Introducing a getSafeRaw() method in RawField (#118)￼</li>
  <li>Various minor build dependency upgrade</li>
</ul>

<p>The Apache James PMC would like to thanks all contributors who made this release possible!</p>
