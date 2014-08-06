# Demo

---

## Usage

```html
<div id="demo">拖拽我</div>
<script>
	seajs.use('jquery-drag', function($){
		$('#demo').drag();
	});
</script>
```

<style>
	
	#demo{
		width: 100px;
		height: 100px;
		text-align: center;
		line-height: 100px;
		font-size: 24px;
		background: #f5f5f5;
		border: 10px solid #ddd;
		z-index: 1;
	}

</style>

<div id="demo">拖拽我</div>

<script>
	seajs.use('jquery-drag', function($){
		$('#demo').drag();
	});
</script>
