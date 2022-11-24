---
Title: CSS
Description: Page about CSS
---

<div class="s-tech-container">
    <div class="tech-sidebar">
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="css">CSS</a></p>
        <p><a href="html">HTML</a></p>
        <p><a href="javascript">JavaScript</a></p>
        <p><a href="php">PHP</a></p>
        <p><a href="python">Python</a></p>
        <p><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
    <div class="tech-info">
        <span class="underline"><h1>CSS</h1></span>
        <p style="margin-top: 20px">Cascading Style Sheets är språk för att beskriva utseende av element i ett markup language till exempel HTML. CSS är en av tre teknologier som utgör fundamentet för webben.</p>
        <p>I CSS använder vi selektorer för att beskriva vilka element vi vill påverka och deklarerar sedan stilen för elementen i ett block.</p>
        <p>Om vi till exempel vill sätta färgen för alla textstycken till blå gör vi på följande sätt.</p>
        <p style="margin-bottom:10px;">HTML använder sig av element beskrivna av taggar. Nedan är ett exempel på ett textstycke med en länk i:</p>
        <pre><code class="language-html">
            p {
                color: blue;
            }
            </code></pre>
    </div>
</div>