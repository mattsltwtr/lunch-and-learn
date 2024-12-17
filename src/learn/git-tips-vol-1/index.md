# Git Lunch and Learn: Vol. 1

---
## How to avoid Merge Conflicts 100% of the time

<div class="fragment">

![alt text](https://emojis.slackmojis.com/emojis/images/1643514947/9702/crying-sunglasses-cowboy.png?1643514947) 

You can't
</div>

---

## How to avoid a lot of Merge Conflicts

<p class="fragment">
Precise staging for commits
</p>

<p class="fragment">
In terms of plating food
</p>

---
<section>
<section data-background-imagex="/images/burgers.webp">

<div class="r-stack">
<div>

### Level 1: Staging Everything

<pre>
<code>
git add .
</code>
</pre>
</div>

<img class="fragment" style="max-height: 50vh;" src="/images/burgers.webp" />

</div>
</section>


<section>
Staging Everything in the Command Line
<iframe src="https://giphy.com/embed/VFMQcgsdeWGEP4m65t" frameBorder="0" class="r-stretch" allowFullScreen></iframe>
</section>
<section>
Staging Everything in VSCode
<iframe src="https://giphy.com/embed/lllg2EZNQSu4G1iEYK" frameBorder="0" class="r-stretch" allowFullScreen></iframe>
</section>

<section>

### 👍
### What it's great for
- Small number of files changed
- Each file was manipulated by you
</section>
<section>

### 🙅🏻
### What it's not great for
- Large number of files changes
- Files that you didn't change are modified
</section>
</section>

---
<section>

<section data-background-imagex="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExcjhjZHdhbXNndXdiamVjZjZnenExdXVyN2V2aHMxMzBkZDZyM29xbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9dg/aJ9Fk5rtz7nBAojxkE/giphy.gif">

<div class="r-stack">
<div>

### Level 2: Staging Specific Files

<pre>
<code>
git add theme/sections/frames.liquid
</code>
</pre>
</div>

<img class="fragment" src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExcjhjZHdhbXNndXdiamVjZjZnenExdXVyN2V2aHMxMzBkZDZyM29xbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9dg/aJ9Fk5rtz7nBAojxkE/giphy.gif" />
</div>
</section>

<section>
Staging a file in the Command Line
<iframe src="https://giphy.com/embed/Wrd4WkCF9J824494rA" frameBorder="0" class="r-stretch" allowFullScreen></iframe>
</section>
<section>
Staging a file in VSCode
<iframe src="https://giphy.com/embed/rsEckfm9T1Y4fZxuxL" frameBorder="0" class="r-stretch" allowFullScreen></iframe>
</section>


<section>

### 👍
### What it's great for
- Large number of files changed
- You can identify all the files you changed
</section>
<section>

### 🙅🏻
### What it's not great for
- Files that contain generated schema
</section>
</section>

---
<section>
<section data-background-imagex="https://64.media.tumblr.com/eeb1cabffc253d3bf7412e0f38573a3d/14b0f0ed966330d3-e0/s540x810/0a6eadcb2b80ab246f83ecc68dccc7d58c0b5198.gifv">

<div class="r-stack">
<div>

### Level 3: Staging Hunks/Blocks
<pre>
<code data-noescape>
git add theme/sections/frames.liquid -p
</code>
</pre>
</div>


<img class="fragment" src="https://64.media.tumblr.com/eeb1cabffc253d3bf7412e0f38573a3d/14b0f0ed966330d3-e0/s540x810/0a6eadcb2b80ab246f83ecc68dccc7d58c0b5198.gifv"/>
</div>
</section>

<section>
Staging Hunks in the Command Line

<iframe src="https://giphy.com/embed/f1TywIx8RbldGMk32U" frameBorder="0" class="r-stretch" allowFullScreen></iframe>
</section>
<section>
Staging Blocks in VSCode

<img src="/images/staging-block.gif"/>
</section>

<section>

### 👍
### What it's great for
- Small changes you made
- Changes in files with generated schemas
</section>
<section>

### 🙅🏻
### What it's not great for
- Staging all the changes in a file
- A file being added or deleted
</section>
</section>

---

Formatters causing issues

---

## Resolving Conflicts as they arise 
- Referencing the Cloud Repository
- VSCode Classic merge Resolution
- Diffing Files Manually
- VSCode Merge Editor
