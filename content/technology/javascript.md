---
Title: JavaScript
Description: Page about JavaScript
---

<div class="s-tech-container">
<div class="side-bar-wrapper">
    <div class="tech-sidebar">
        <p><a href="css">CSS</a></p>
        <p><a href="html">HTML</a></p>
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="javascript">JavaScript</a></p>
        <p><a href="php">PHP</a></p>
        <p><a href="python">Python</a></p>
        <p><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
</div>
    <div class="tech-info">
        <span class="underline"><h1>JavaScript</h1></span>
        <p style="margin-top: 20px">JavaScript är ett prototyp-baserat skriptspråk. JavaScript utgör tillsammans med HTML och CSS grunden för webben. JavaScript är dynamiskt, svagt typat och hanterar funktioner som första-klass-objekt.</p>
        <p>JavaScript använder sig av C-like syntax, men har annars inget gemensamt med programmeringsspråket Java.</p>
        <p style="margin-bottom:10px;">Ett program som skriver ut alla jämna siffror mellan 1 och 100 kan se ut på följande sätt i JavaScript:</p>
        <pre>
        <code class="language-html">for (let i = 1; i &lt;= 100; i++) {
    if (!(i % 2)) {
        console.log(i);
    }
}
            </code></pre>
    </div>
</div>