---
layout: page
---
<div class="index-artical">
   <form action="upload" method="post">
		<tr>
			<td><i>I see myself as:</i></td><br>
			<td>1. <input type="text" name="q1" size="1" style=" border:none; border-bottom:1px #000000 solid;">Extraverted, enthusiastic.</td><br>
			<td>2. <input type="text" name="q2" size="1" style=" border:none; border-bottom:1px #000000 solid;">Critical, quarrelsome.</td><br>
			<td>3. <input type="text" name="q3" size="1" style=" border:none; border-bottom:1px #000000 solid;">Dependable, self-disciplined.</td><br>
			<td>4. <input type="text" name="q4" size="1" style=" border:none; border-bottom:1px #000000 solid;">Anxious, easily upset.</td><br>
			<td>5. <input type="text" name="q5" size="1" style=" border:none; border-bottom:1px #000000 solid;">Open to new experiences, complex.</td><br>
			<td>6. <input type="text" name="q6" size="1" style=" border:none; border-bottom:1px #000000 solid;">EReserved, quiet.</td><br>
			<td>7. <input type="text" name="q7" size="1" style=" border:none; border-bottom:1px #000000 solid;">Sympathetic, warm.</td><br>
			<td>8. <input type="text" name="q8" size="1" style=" border:none; border-bottom:1px #000000 solid;">Disorganized, careless.</td><br>
			<td>9. <input type="text" name="q9" size="1" style=" border:none; border-bottom:1px #000000 solid;">Calm, emotionally stable.</td><br>
			<td>10. <input type="text" name="q10" size="1" style=" border:none; border-bottom:1px #000000 solid;">Conventional, uncreative.</td><br>
		</tr>
		<input type="submit" value="Submit" />
	</form>
</div>

<script type="text/javascript">
$(function(){
    var height = $('.index-artical').height();
    $('.index-mid').height(height-90);
});
</script>
