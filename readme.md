# PyGame - Ride The Wind

## Story Board
1. Tujuan Game: Menghindari musuh, mendapat 5 koin dan lanjut ke level selanjutnya.
2. Aktor: Pemain dan Musuh.
3. Rule Game: pemain harus melewati musuh, jika mati maka akan game over tetapi kalau berhasil mendapatkan 5 koin maka pemain menang dan lanjut ke level selanjutnya.
4. Aset : Kemungkinan besar asset akan mengambil dari internet yang terbebas dari copyright. Untuk website download asset sendiri terdapat berbagai pilihan.
	- https://itch.io/game-assets/free/tag-2d
	- https://craftpix.net/freebies/
	- https://opengameart.org/
5. Win/Lose:
	- Win : Mendapat 5 Koin.
	- Lose : Nyawa Habis

## Class
a. Pemain dan Musuh
<table style="text-align: center; ">
	<thead>
		<th>Pemain</th>
	</thead>
	<tbody>
		<tr>
			<td> State <br> Speed <br> Lives <br> Image <br> Hitbox </td>
		</tr>
		<tr>
			<td> Method <br> Def Hit <br> Def Draw <br> Def Move <br> Def Death <br> </td>
		</tr>
	</tbody>
</table>

<table style=" text-align: center; ">
	<thead>
		<th>Musuh</th>
	</thead>
	<tbody>
		<tr>
			<td> State <br> Speed <br> Image <br> Hitbox </td>
		</tr>
		<tr>
			<td> Method <br> Def Hit <br> Def Draw <br> Def Move <br> Def Death <br> </td
		</tr>
	</tbody>
</table>


b.Platform dan Coin
<table style="text-align: center; ">
	<thead>
		<th>Platform</th>
	</thead>
	<tbody>
		<tr>
			<td> Image <br> Hitbox </td>
		</tr>
		<tr>
			<td> Method <br> Def Draw </td>
		</tr>
	</tbody>
</table>

<table style="text-align: center; ">
	<thead>
		<th>Coin</th>
	</thead>
	<tbody>
		<tr>
			<td> Position <br> Image <br> Count <br> Hitbox </td>
		</tr>
		<tr>
			<td> Def Hit <br> Def Draw </td>
		</tr>
	</tbody>
</table>
