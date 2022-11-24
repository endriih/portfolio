---
Title: Python
Description: Page about Python
---

<div class="s-tech-container">
    <div class="tech-sidebar">
        <p><a href="css">CSS</a></p>
        <p><a href="html">HTML</a></p>
        <p><a href="javascript">JavaScript</a></p>
        <p><a href="php">PHP</a></p>
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="python">Python</a></p>
        <p><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
    <div class="tech-info">
        <span class="underline"><h1>Python</h1></span>
        <p style="margin-top: 20px">Python är ett programmeringsspråk som lanserades 1991 av Guido van Rossum. Programmeringsspråket är dynamiskt typad och betecknas som ett generellt programmeringsspråk då det kan tillämpas inom många domäner.</p>
        <p>Programmeringsspråket utmärkar sig genom att alla datatyper är baserat på klasser och objekt. En annan aspekt som skiljer Python från andra språk är att indentering används för att särskilja block i koden.</p>
        <p style="margin-bottom:10px;">Ett program som skriver ut alla jämna siffror mellan 1 och 100 kan se ut på följande sätt i Python:</p>
        <pre><code>
            for number in range(1, 100 + 1):
            if not number % 2:
            print(number)
        </code></pre>
    </div>
</div>