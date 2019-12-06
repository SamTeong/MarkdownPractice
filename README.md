# Github Markdown

## Text Formatting

<table>
	<tr>
		<td><b>Bold</b></td>
		<td>**text**<br/>__text__</td>
	</tr>
	<tr>
		<td><em>Italic</em></td>
		<td>*text*<br/>_text_</td>
	</tr>
	<tr>
		<td><strike>Strikethrough</strike></td>
		<td>~~text~~</td>
	</tr>
	<tr>
		<td>Hyperlink</td>
		<td>[display text](http://google.com)</td>
	</tr>
</table>

## Lists

<table>
	<tr>
		<td>Ordered List</td>
		<td>Unordered List (*, -, +)</td>
	</tr>
	<tr>
		<td>1. One<br/>
			2. Two<br/>
			3. Three</td>
		<td>- One<br/>
			- Two<br/>
			- Three<br/>
			&nbsp;&nbsp;- Use two spaces to indent</td>
	</tr>
</table>

## Images

<p>![display text](https://octodex.github.com/images/yaktocat.png)</p>

![image](https://octodex.github.com/images/yaktocat.png)
*Unable to resize by markdown*

## Document Structure

<table>
	<tr>
		<td># Heading 1</td>
		<td><h1>Heading 1</h1></td>
	</tr>
	<tr>
		<td>## Heading 2</td>
		<td><h2>Heading 2</h2></td>
	</tr>
	<tr>
		<td>### Heading 3</td>
		<td><h3>Heading 3</h3></td>
	</tr>
	<tr>
		<td>#### Heading 4</td>
		<td><h4>Heading 4</h4></td>
	</tr>
	<tr>
		<td>##### Heading 5</td>
		<td><h5>Heading 5</h5></td>
	</tr>
	<tr>
		<td>###### Heading 6</td>
		<td><h6>Heading 6</h6></td>
	</tr>
	<tr> 
		<td> </td>
		<td> </td>
	</tr>
	<tr> 
		<td>> Quote something<br/>
			> - Someone</td>
		<td>
			<blockquote>
				Quote something<br>
				&bull; Someone
		    </blockquote>
		</td>
	</tr>
</table>

## Code

<table>
	<tr>
		<td>
			&nbsp;&nbsp;&nbsp;&nbsp;if (conditional) {<br/>
			&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return true;<br/>
			&nbsp;&nbsp;&nbsp;&nbsp;}
		</td>
		<td>
			<pre><code>
if (conditional) {
    return true;
}
			</code></pre>
		</td>
	</tr>
	<tr>
		<td>`inline code`</td>
		<td><code>inline code</code></td>
	</tr>
	<tr>
		<td>
			```javascript<br/>
			if (conditional) {<br/>
			&nbsp;&nbsp;&nbsp;&nbsp;return true;<br/>
			}<br/>
			```
		</td>
		<td>
			<pre><code>
if</span> (conditional) { 
	return true;
}
			</code></pre>
			*Keywords will be colored. Not working here.
		</td>
	</tr>
</table>

## Others

<table>
	<tr>
		<td>Tagging</td>
		<td>@someone</td>
	</tr>
	<tr>
		<td>
			- [x] item 1<br/>
			- [ ] item 2</td>
		<td>
			&#x2612; item 1<br/>
			&#x2610; item 2
		</td>
	</tr>
	<tr>
		<td>
			First Header | Second Header<br/>
			------------ | -------------<br/>
			First Column Content | Second Column Content
		</td>
		<td>
			<table>
				<tr>
					<th style="text-align:left;">First Header</th>
					<th style="text-align:left;">Second Header</th>
				</tr>
				<tr>
					<td>First Column Content</td>
					<td>Second Column Content</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

