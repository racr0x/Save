<!DOCTYPE html>
<html lang="en">
   <head>
	 <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.0.0/mermaid.min.js"></script>
    </head>
	 
<body>

<!--################################################################
##          SSSSSS        A    VV         VV EEEEEEEE         ## 
##         SS            AAA    VV       VV  EE               ##
##         SS           AA AA    VV     VV   EE               ##
##          SSSSS      AA   AA    VV   VV    EEEEEEEE         ##
##              SS    AAAAAAAAA    VV VV     EE               ##
##              SS   AA       AA    VVV      EE               ##
##         SSSSSA   AA         AA    V       EEEEEEEE         ##
################################################################
-->
 <pre><code class="language-mermaid">graph LR
A--&gt;B
</code></pre>

<div class="mermaid">graph LR
A--&gt;B
</div>
	
</body>
<script>
var config = {
    startOnLoad:true,
    theme: 'forest',
    flowchart:{
            useMaxWidth:false,
            htmlLabels:true
        }
};
mermaid.initialize(config);
window.mermaid.init(undefined, document.querySelectorAll('.language-mermaid'));
</script>

</html>
