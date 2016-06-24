findInPage
==========

Usage
-----
```html
<div class="search">
	Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit magni consequuntur ex perferendis iusto tempora omnis id 
	<div>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perspiciatis, dignissimos atque enim, debitis nesciunt unde ipsum? Saepe fugiat molestias consequuntur quam, inventore quod nulla! At tempora molestiae sed consequatur ipsam.
		</p>
	</div>accusamus qui dicta, fugit fugiat necessitatibus. Consectetur eos, eveniet aperiam consequatur ipsa reiciendis!
</div>
<script>
$(".search").findInPage({keyword:"am"});
</script>
```

Option
-----

- tag (which element tag to use to enclose the strings)
- mark (className of the tag to highlight the strings)
- caseSensitive (If you want to search words with the correct case, set it as true)
