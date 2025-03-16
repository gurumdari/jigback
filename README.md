<p align="center">
	<img src="images/jigback.png?raw=true" width="468" /><br>
	<a href="https://jigback.org" target="_blank">https://jigback.org</a>
</p>

### Back-end module for JigTime (Support various platforms)

<p align="center"><img src="images/backend.png?raw=true" width="850" /></p>

### Reusable data-binding over template by MVC pattern

<p align="center"><img src="images/resolver.png?raw=true" width="850" /></p>

### Transpiling and minifying templates

<p align="center"><img src="images/transpile.png?raw=true" width="490" /></p>

> JS/CSS templates and static HTML page templates are transpiled in the back-end via deno, but HTML SPA resource templates are rendered in JigTime (Natural JavaScript) of the front-end.

<p align="center"><img src="images/template_engine.png?raw=true" width="490" /></p>

### Transpiling and rendering dynamic HTML page templates

<p align="center"><img src="images/render.png?raw=true" width="765" /></p>

### Separate directories into protected and public

<table>
	<tbody>
		<tr>
			<td><b>Protected</b></td>
			<td>
				<ul>
					<li>Manage business implementation files on the back-end platform</li>
					<li>Manage source files to be transpiled and minified</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td><b>Public</b></td>
			<td>
				<ul>
					<li>Serving static files such as images</li>
					<li>Serving transpiled and minified result files</li>
				</ul>
			</td>
		</tr>
	</tbody>
</table>

### Development independent of back-end platform

> Instead of JigBack, which supports various back-end platforms, SPA development is possible with only JigTime, which is implemented in natural JavaScript.

<p align="center">
	<img src="images/jigtime.png?raw=true" width="200" /><br>
	<a href="https://jigtime.org" target="_blank">https://jigtime.org</a>
</p>