<template>
	<div class="box_inventory">
		<table>
			<tbody>
				<tr>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
					<td>5</td>
				</tr>
				<tr>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
				</tr>
				<tr>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
				</tr>
				<tr>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
				</tr>
				<tr>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
					<td></td>
				</tr>
			</tbody>
		</table>
	</div>
</template>

<script lang="ts">
export default {
	setup() {
		return {}
	},
}
</script>

<style lang="scss" scoped>
@use '../assets/global.scss' as *;

.box_inventory {
	width: 525px;
	border: 1px solid $dark-border;
	border-radius: 12px;
	height: 500px;
	overflow: hidden;
}

table {
	width: 525px;
	height: 500px;
	border-collapse: collapse;
}

td {
	cursor: grab;
	border: 1px solid $dark-border;
	text-align: center;
	width: 105px;
	height: 100px;
}
</style>
