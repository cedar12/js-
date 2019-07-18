# js-定时任务
> 使用示例
```
<script src="task.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript">
	const t=new Task('s%5=0');//每5秒执行
	t.update(()=>{
		console.log('执行...');
	});
	console.log(t.help());//打印使用示例和表达式说明
</script>
```
