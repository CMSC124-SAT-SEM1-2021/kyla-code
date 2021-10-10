## Grammar
&lt;syntax&gt; -> begin &lt;block&gt; end
&lt;block&gt; -> &lt;assign&gt;; | &lt;block&gt;
&lt;assign&gt; -> &lt;id&gt; = &lt;expr&gt;
&lt;expr&gt; -> &lt;expr&gt; &lt;op&gt; &lt;expr&gt; | &lt;id&gt; &lt;op&gt; &lt;id&gt; | &lt;id&gt; &lt;op&gt; &lt;expr&gt; | (&lt;expr&gt;)
&lt;op&gt; -> + | - | * | /
&lt;id&gt; -> A | B | C