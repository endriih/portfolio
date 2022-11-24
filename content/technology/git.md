---
Title: Git
Description: Page about Git
---

<div class="s-tech-container">
    <div class="tech-sidebar">
        <p><a href="css">CSS</a></p>
        <p><a href="html">HTML</a></p>
        <p><a href="javascript">JavaScript</a></p>
        <p><a href="php">PHP</a></p>
        <p><a href="python">Python</a></p>
        <p {% if page.id==current_page.id %} class="active" {% endif %}><a href="git">Git</a></p>
        <p><a href="sqlite">SQLite</a></p>
    </div>
    <div class="tech-info">
        <span class="underline"><h1>Git</h1></span>
        <p style="margin-top: 20px">Git är ett distribuerat versionshanteringssystem som skapades 2005 av Linus Torvalds. Git skapades för att hantera ändringar för Linux-kärnan.</p>
        <p>Att Git är ett distribuerat system innebär att inget centralt arkiv behövs. Ett centralt arkiv behövs dock om flera utvecklare vill samarbeta om samma kod.</p>
        <p style="margin-bottom:10px;">Git är tradionellt sett ett CLI verktyg, men en del GUI baserade verktyg har utvecklats för att underlätta tröskeln att börja med Git.</p>
    </div>
</div>