<h1 id="understanding-a-tags-in-html">Understanding <code>a</code> tags in HTML</h1>
<p>The <code>a</code> tag is a fundamental HTML element responsible for much of the linking goodn ess that makes HTML great!</p>
<h2 id="components">Components</h2>
<p>Let's take a quick look at how the tag works:</p>
<div class="sourceCode"><pre class="sourceCode html"><code class="sourceCode html"><span class="kw">&lt;a</span><span class="ot"> href=</span><span class="st">&quot;sourceurl&quot;</span><span class="kw">&gt;</span>Displayed Text<span class="kw">&lt;/a&gt;</span></code></pre></div>
<p>As in any tag, there's a basic structure of <code>&lt;tag attr=&quot;value&quot;&gt;content&lt;/tag&gt;</code>. The fantastic, amazing attribute in the <code>a</code> tag is <code>href</code> -- short for &quot;hypertext reference&quot;. The <code>href</code> attribute identifies a target URL; when this HTML snippet is displayed in a browser, the browser will direct you to the URL in the href attribute. Let's try it out:</p>
<div class="sourceCode"><pre class="sourceCode html"><code class="sourceCode html"><span class="kw">&lt;a</span><span class="ot"> href=</span><span class="st">&quot;https://google.com&quot;</span><span class="kw">&gt;</span>Google Owns All Your Data<span class="kw">&lt;/a&gt;</span></code></pre></div>
<p><a href="https://google.com">Google Owns All Your Data</a></p>
<p>As with most HTML tags, the <code>a</code> tag accepts a number of possible attributes. Some of them are used only rarely, but you will often see the <code>target</code> attribute in the real world. THis allows you to specify where to open the link you click on:</p>
<ul>
<li><code>_self</code> means &quot;open here&quot;</li>
<li><code>_blank</code> means &quot;open in a new tab&quot;</li>
<li><code>_parent</code> means &quot;if you're looking at an <a href="https://developer.mozilla.org/en/docs/Web/HTML/Element/iframe">internal frame</a>, open this link in the frame's arent tab. Otherwise, just open here like in <code>_self</code></li>
</ul>
<h2 id="learn-more">Learn More</h2>
<p>The <a href="https://developer.mozilla.org/en/docs/Web/HTML/Element/a">Mozilla Developer Network</a> has lots more detail about this and every HTML tag!</p>
