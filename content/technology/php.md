---
Title: PHP
Description: Page about PHP
---

<div class="s-tech-container">
<div class="side-bar-wrapper">
    <div class="tech-sidebar">
        <p><a href="css">CSS</a></p>
        <p><a href="html">HTML</a></p>
        <p><a href="javascript">JavaScript</a></p>
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="php">PHP</a></p>
        <p><a href="python">Python</a></p>
        <p><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
</div>
    <div class="tech-info">
        <span class="underline"><h1>PHP</h1></span>
        <p style="margin-top: 20px">PHP är ett populärt skriptspråk som främst används för att skapa webbplatser med dynamiskt innehåll. PHP är det mest använda server-side programmeringsspråk på webben med uppåt 80% av alla webbplatser som använder det.</p>
        <p>PHP är ett objekt-orienterad programmeringsspråk, som med senare versioner kan vara hård typat och till och med JIT.</p>
        <p style="margin-bottom:10px;">Ett program som skriver ut alla jämna siffror mellan 1 och 100 kan se ut på följande sätt i JavaScript:</p>
        <pre><code>&lt;?php
        
for ($i = 1; $i &lt;= 100; $i++) {
    if (!($i % 2)) {
        print($i);
    }
}</code></pre>
    </div>
</div>