---
Title: HTML
Description: Page about HTML
---

<div class="s-tech-container">
    <div class="side-bar-wrapper">
    <div class="tech-sidebar">
        <p><a href="css">CSS</a></p>
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="html">HTML</a></p>
        <p><a href="javascript">JavaScript</a></p>
        <p><a href="php">PHP</a></p>
        <p><a href="python">Python</a></p>
        <p><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
    </div>
    <div class="tech-info">
        <span class="underline"><h1>HTML</h1></span>
        <p style="margin-top: 20px">HyperText Markup Language (HTML) utgör tillsammans med HyperText Transfer Protocol (HTTP) grunden i webben. Webbsidor skrivs i HTML och skickas sedan över internet med hjälp av HTTP.</p>
        <p>HTML beskriver innehåll och struktur för våra webbplatser och gör det möjligt att ladda andra dokument till exempel CSS eller JavaScript filer.</p>
        <p style="margin-bottom:10px;">HTML använder sig av element beskrivna av taggar. Nedan är ett exempel på ett textstycke med en länk i:</p>
        <pre>
            <code>&lt;p&gt;En länk till min &lt;a href="minwebbplats.html"&gt;webbplats&lt;/a&gt;&lt;/p&gt;
            </code></pre>
    </div>
</div>