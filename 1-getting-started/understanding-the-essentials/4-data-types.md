---
description: Easily identify data types using the color legend
---

# 4-Data Types

Since Onum can process any data type, you may be wondering how to identify which is which. See the color legend below:

<table><thead><tr><th width="170.2769775390625">Field type</th><th width="323.133544921875">Description</th><th>Example</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/string.png" alt="" data-size="line"></td><td>A sequence of characters that is used primarily for textual data representation.</td><td><pre><code>"hello world"
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/liststring4.png" alt="" data-size="line"></td><td>A list of string values separated by commas.</td><td><pre data-overflow="wrap"><code>"hello", "my", "name", "is", "John"
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/int.png" alt="" data-size="line"></td><td>Used to represent whole numbers without any fractional or decimal component. Integers can be positive, negative, or zero.</td><td><pre><code>25
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/listinteger.png" alt="" data-size="line"></td><td>A list of integer values separated by commas.</td><td><pre><code>1, 2, 3, 4
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/fllot.png" alt="" data-size="line"></td><td>Used to represent real numbers with fractional parts, allowing for the representation of a wide range of values, including decimals.</td><td><pre><code>1.2
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/lllist.png" alt="" data-size="line"></td><td>A list of float values separated by commas.</td><td><pre><code>0.1, -1.0, 2.0
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/timestamp.png" alt="" data-size="line"></td><td>Sequence of characters or encoded information that identifies the precise time at which an event occurred.</td><td><pre><code>2024-05-17T14:30:00Z
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/listtimestamp.png" alt="" data-size="line"></td><td>A list of timestamps separated by commas.</td><td><pre data-overflow="wrap"><code>2024-05-17T14:30:00Z, 2022-10-19T14:30:04Z, 1998-04-10T14:49:00Z
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/boolean.png" alt="" data-size="line"></td><td>A fundamental data type in computer programming that represents one of two possible values: <code>true</code> or <code>false</code>.</td><td><pre><code>true
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/listboolean.png" alt="" data-size="line"></td><td>A list of boolean values separated by commas.</td><td><pre><code>true, false, true
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/chip-csv.png" alt="" data-size="line"></td><td>A simple and widely used file format for storing tabular data, such as a spreadsheet or database. In a CSV file, each line of the file represents a single row of data, and fields within each row are separated by a delimiter, usually a comma.</td><td><p></p><pre class="language-csv"><code class="lang-csv"><strong>id,name,price
</strong>1,Apple,0.99
2,Banana,0.59
3,Cherry,1.29
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/image.png" alt="" data-size="line"></td><td>XML (Extensible Markup Language) is a markup language designed for encoding documents in a format that is both human-readable and machine-readable.</td><td><pre class="language-xml" data-overflow="wrap"><code class="lang-xml">&#x3C;Book>
    &#x3C;Title>Example Title&#x3C;/Title>
    &#x3C;Author>Author Name&#x3C;/Author>
&#x3C;/Book>
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/chip-json.png" alt="" data-size="line"></td><td>In a JSON, fields are represented by keys within objects, and the corresponding values can be of any JSON data type. This flexibility allows a JSON to represent structured data in a concise and readable manner, making it suitable for various applications, especially in web development and API communication.</td><td><p></p><pre class="language-json" data-overflow="wrap"><code class="lang-json">{
  "items": [
    {
      "id": 1,
      "name": "Apple"
    },
    {
      "id": 2,
      "name": "Banana"
    },
    {
      "id": 3,
      "name": "Cherry"
    }
  ]
}
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/kvl.png" alt="" data-size="line"></td><td>A key-value pair is a data structure commonly used in various contexts, including dictionaries, hash tables, and associative arrays. It consists of two components: a key and its corresponding value.</td><td><pre><code>name = Alice
age = 30
city = Paris
</code></pre></td></tr><tr><td><img src="../../.gitbook/assets/chip-delimiter.png" alt="" data-size="line"></td><td>Characters that separate individual fields or columns of data. The delimiter ensures that each piece of data within a row is correctly identified and separated from the others.</td><td><pre><code>/
</code></pre></td></tr></tbody></table>
