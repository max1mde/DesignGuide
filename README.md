<div align="center">
  <h1>The Design Guide</h1>
  <p>A simple design guide for everything related to Git and Github (especially Markdown)</p>
  <img src="https://github.com/max1mde/DesignGuide/assets/114857048/1c109e37-3501-4581-8273-2595593b3219">
  <div>
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/max1mde/DesignGuide">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/max1mde/DesignGuide">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/max1mde/DesignGuide">
    <img alt="GitHub license" src="https://img.shields.io/github/license/max1mde/DesignGuide">
  </div>  
</div>

# About This Project

This project is here to help you get inspired and learn how to make your README files and other project content look better. It gives you ideas and tips that can be really helpful, but you don't have to do everything exactly as it says.

**Feel free to:**
- Use this guide for your own projects
- Contribute to this project if you see something that can be improved or added

# Categories
<!--------------------------------------Markdown in general-------------------------------------->
<details>
<summary>Markdown</summary>
<a href="https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">Here is the source</a> of the following information  
<h3>Headings</h3>
<pre>  
# A first-level heading<br>
## A second-level heading<br>
### A third-level heading<br>
<h1>A first-level heading</h1>
<h2>A second-level heading</h2>
<h3>A third-level heading</h3>
</pre>
<h3>Text formatting</h3>
<pre>  
**This is bold text**
<b>This is bold text</b>
<br>
_This text is italicized_
<i>This text is italicized</i>
<br>
~~This was mistaken text~~
<strike>This was mistaken text</strike>  
<br>  
> Text that is a quote
<blockquote>Text that is a quote</blockquote>
</pre>  
<h3>Colors</h3>
  
> **Note**  
> Color visualization is supported only in Issues, Pull Requests and Discussions.
<pre>
`#0969DA`
`rgb(9, 105, 218)`
`hsl(212, 92%, 45%)`<br> 
<img src="https://github.com/max1mde/DesignGuide/assets/114857048/765e8bd5-efab-4c51-9c0b-18962cd39c49" width="150">
</pre>
<h3>Links</h3>
<pre>  
[This is a link](https://github.com/max1mde/DesignGuide)
<a href="https://github.com/max1mde/DesignGuide">This is a link</a><br>
[License of this project](LICENSE)
<a href="LICENSE">License of this project</a><blockquote>Relative link</blockquote></pre>  
<h3>Lists</h3>
<pre>    
- First list item
- Second list item
- Third list item
<ul>
<li>First list item</li>
<li>Second list item</li>
<li>Third list item</li>
</ul></pre>    
<h3>TODO Lists</h3>
<pre>    
- [x] A todo which is done
- [ ] An issue https://github.com/max1mde/HologramAPI/issues/1<br>

- [x] A todo which is done
- [ ] An issue https://github.com/max1mde/HologramAPI/issues/1</pre>

<h3>Highlight "Note", "Important" and "Warning" blockquotes</h3>

```
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

<img src="https://github.com/user-attachments/assets/59ae0c4b-49ce-4bbf-8c4b-3457a96caa7a" width="600">

<h3>Emojies</h3>

| icon | shortcode | icon | shortcode |
| :-: | - | :-: | - |
| 😄 | `:grinning:` | 😃 | `:smiley:` |
| 😄 | `:smile:` | 😁 | `:grin:` |
| 😆 | `:laughing:` `:satisfied:` | 😅 | `:sweat_smile:` |
| 🤣 | `:rofl:` | 😂 | `:joy:` |
| 🙂 | `:slightly_smiling_face:` | 🙃 | `:upside_down_face:` |
| 😉 | `:wink:` | 😊 | `:blush:` |

<a href="https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md">Here you can find a list of all emojies</a>


<h3>HTML</h3>
You might have already seen that you can use HTML tags, like the &lt;a&gt; or &lt;img&gt; tags in a Markdown file.<br>
But there are more tags you can use.<br>
You will probably find a tag for every Markdown feature and even more tags.<br>
HTML tags give you more possibilities and control.<br>
<br>

For example, you can center any element by surrounding it with this div.<br>
<pre>
&lt;div align="center"&gt;
  &lt;!--- elements to center --&gt;
&lt;/div&gt;
</pre>

Maybe you want to change the size of an image<br>
<pre>
&lt;img src="image.png" width="200"&gt;
</pre>

Or create a collapsible section

<pre>
&lt;details>
&lt;summary&gt;The title&lt;/summary&gt;
  &lt;p&gt;And the hidden content&lt;/p&gt;
&lt;/details&gt;
</pre>

Which would look like this:
<details>
<summary>The title</summary>
  <p>And the hidden content</p>
</details>

<h3>HTML Symbols and Entities</h3>
When writing HTML, you might want to display certain symbols, like `<`, `>`, or `&` without having them interpreted as HTML tags. For this, you can use HTML entities, which are special codes that represent characters.

HTML entities always start with an `&` and end with a `;`. Here are some common ones:

* `&lt;` — Represents `<` (less-than symbol)
* `&gt;` — Represents `>` (greater-than symbol)
* `&amp;` — Represents `&` (ampersand)
* `&quot;` — Represents `"` (double quote)
* `&#39;` — Represents `'` (single quote)

These entities are especially useful in documentation or README files where you might want to show code snippets that include HTML tags without them being interpreted as actual HTML.

For example, if you want to display the text `<div align="center">` without it being treated as an HTML tag, you would write:<br>

`&lt;div align="center"&gt;`

Other useful HTML entities:
- `&copy;` — © symbol
- `&reg;` — ® symbol
- `&euro;` — € symbol
- `&yen;` — ¥ symbol
- `&trade;` — ™ symbol

</details>
<!--------------------------------------Repo readme-------------------------------------->
<details>
<summary>Repository readme</summary>
<h3>Structure</h3>

<pre>• Badges  (optional)
• Title
• Description
• Banner/Showcase of the project  (optional)
• Table of Contents (optional but good for big readme's)
• Installation
• Usage
• How to Contribute, Licence, Credits etc  (optional)</pre>
--------------------------------------------
<h3>Badges</h3>
Badges display important details about a project, such as version, license, downloads, and ratings. These badges can be either static or dynamic and also include symbols. These small graphical elements are typically found at the top of your readme and are provided by various services like <a href="https://shields.io">shields.io</a>. 
<br>
<br>
<pre><b>You can use the html image tag to display a badge:</b><br><br>&lt;img alt="GitHub license" src="https://img.shields.io/github/license/max1mde/DesignGuide"&gt;<br><br><img alt="GitHub license" src="https://img.shields.io/github/license/max1mde/DesignGuide"></pre>

<pre><b>You can also make them clickable by enclosing the &lt;img&gt; element within an &lt;a&gt; element, like this:</b><br>
&lt;a href="https://github.com/max1mde/DesignGuide/blob/main/LICENSE"><br>  &lt;img alt="GitHub license" src="https://img.shields.io/github/license/max1mde/DesignGuide"&gt;<br>&lt;/a&gt;<br><br><a href="https://github.com/max1mde/DesignGuide/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/max1mde/DesignGuide"></a></pre>

</details>
<!--------------------------------------Profile readme-------------------------------------->
<details>
<summary>Profile readme</summary>
<p>Nothing here yet. You can change this by opening a pull request and contributing to this project</p>
</details>

<details>
<summary>Wiki</summary>
<p>Nothing here yet. You can change this by opening a pull request and contributing to this project</p>
</details>
<!--------------------------------------Commit messages-------------------------------------->
<details>
<summary>Commits</summary>
<h3>Commit messages</h3>
<p>Writing clear commit messages is crucial for a clean Git history</p>
<ul>
  <li>Keep messages concise.</li>
  <li>Use imperative mood.</li>
  <li>Separate subject from body.</li>
  <li>Reference issues if applicable.</li>
  <li>Use emojis wisely.</li>
</ul>

<p>Emojis enhance commit messages, conveying change nature visually. They provide a quick understanding.</p>
<p>Here's how you can use them for different changes:</p>
<ul>
  <li>🐛 Fixing a bug</li>
  <li>📝 Updating code/documentation</li>
  <li>🚀 Introducing a new feature</li>
  <li>🔒 Fixing a security issue</li>
  <li>🧹 Refactoring code</li>
  <li>📈 Improving performance</li>
  <li>🗑️ Removing code</li>
  <li>↗️ Upgrading dependencies</li>
  <li>↙️ Downgrading dependencies</li>
  <li>📋 Adding comments</li>
  <li>➕ Adding new code</li>
</ul>
<p>For more examples of what emojies you can use in your commit messages, <a href="https://gitmoji.dev">check out this website.</a></p>
</details>
