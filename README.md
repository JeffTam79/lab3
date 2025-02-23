# Lab 3
## Content Structure (HTML5)

- [My website on Pages](https://jefftam79.github.io/lab3/)

### The Content Covered:
1. Doctype Declaration
2. Header Element
3. Navigation Links Element
4. Main Element
5. Section Element
6. Figure Element
7. Aside Element
8. Footer (`&copy;`) Element
9. Article Element
10. Emphasis Element

### HTML Tag Cheat Sheet
<table>
    <thead>
        <tr>
            <th>Syntax</th>
            <th>Description</th>
            <th>Example</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <pre><code>&lt;!DOCTYPE html&gt;</code></pre>
            </td>
            <td>A declaration that defines the document type and version of HTML being used. It helps the browser render the page correctly.</td>
            <td>
                <pre><code>&lt;!DOCTYPE html&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;header&gt;&lt;/header&gt;</code></pre>
            </td>
            <td>A tag used to represent introductory content, typically containing navigation, branding, or a header for a section or page.</td>
            <td>
                <pre><code>&lt;header&gt;
    &lt;h1&gt;Welcome to My Website&lt;/h1&gt;
    &lt;nav&gt;...navigation links here...&lt;/nav&gt;
&lt;/header&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;nav&gt;&lt;/nav&gt;</code></pre>
            </td>
            <td>A tag used to define a section of navigation links for a website.</td>
            <td>
                <pre><code>&lt;nav&gt;
    &lt;a href="#home"&gt;Home&lt;/a&gt;
    &lt;a href="#about"&gt;About&lt;/a&gt;
    &lt;a href="#contact"&gt;Contact&lt;/a&gt;
&lt;/nav&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;main&gt;&lt;/main&gt;</code></pre>
            </td>
            <td>A tag used to represent the main content of the document. There should be only one <code>&lt;main&gt;</code> element per page.</td>
            <td>
                <pre><code>&lt;main&gt;
    &lt;h2&gt;Article 1&lt;/h2&gt;
    &lt;p&gt;Content of the article goes here.&lt;/p&gt;
&lt;/main&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;section&gt;&lt;/section&gt;</code></pre>
            </td>
            <td>A tag used to group related content, typically with its own heading. It helps structure content into distinct parts.</td>
            <td>
                <pre><code>&lt;section&gt;
    &lt;h2&gt;Introduction&lt;/h2&gt;
    &lt;p&gt;Some introductory text.&lt;/p&gt;
&lt;/section&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;figure&gt;&lt;/figure&gt;</code></pre>
            </td>
            <td>A tag used to encapsulate content such as images, illustrations, or diagrams, often with a caption.</td>
            <td>
                <pre><code>&lt;figure&gt;
    &lt;img src="img/diagram.jpg" alt="Diagram" width="300" height="200"&gt;
    &lt;figcaption&gt;This is a caption for the diagram.&lt;/figcaption&gt;
&lt;/figure&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;aside&gt;&lt;/aside&gt;</code></pre>
            </td>
            <td>A tag used to define content that is tangentially related to the content around it, such as sidebars or additional information.</td>
            <td>
                <pre><code>&lt;aside&gt;
    &lt;p&gt;Related content or links go here.&lt;/p&gt;
&lt;/aside&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;footer&gt;&lt;/footer&gt;</code></pre>
            </td>
            <td>A tag used to define the footer of a page or section. Typically includes copyright, contact, or legal information.</td>
            <td>
                <pre><code>&lt;footer&gt;
    &lt;p&gt;&amp;copy; 2025 My Website&lt;/p&gt;
&lt;/footer&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;article&gt;&lt;/article&gt;</code></pre>
            </td>
            <td>A tag used to represent a self-contained piece of content, such as a blog post, news article, or product description.</td>
            <td>
                <pre><code>&lt;article&gt;
    &lt;h2&gt;Blog Post Title&lt;/h2&gt;
    &lt;p&gt;This is the content of the blog post.&lt;/p&gt;
&lt;/article&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;em&gt;&lt;/em&gt;</code></pre>
            </td>
            <td>A tag used to emphasize text, typically rendering it in italics. It is semantically used for stressing importance.</td>
            <td>
                <pre><code>&lt;p&gt;This is &lt;em&gt;important&lt;/em&gt; text.&lt;/p&gt;</code></pre>
            </td>
        </tr>
    </tbody>
</table>
