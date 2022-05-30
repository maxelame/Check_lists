
# Check_List

ID | Title | Precondition | Inputs | ER| AR | Status |Bug
:------ | :------ | :------ | :------ | :------| :------ | :------ |:------:
1 |	Ввести 6 латинских букв	 |	Остальные поля заполнены валидными данными	 |	Maksim |		Success	 |		pass |		
2 |		Ввести 1 латинскую букву	 | |			M |		Error |			pass |		 |	
3 |		Ввести  2 латинских буквы |	 |		Ma |		Success |		Error |		fail |		ID_1
4 |		Ввести 3 латинских буквы |	 |			Mak |		Success	 |	Error	 |	fail |		ID_2
5 |		Ввести 127 латинских букв	 |	 |		127 букв  |		Success	 |Error |		fail |		ID_3 |	
6 |		Ввести 128 латинских букв	 |	 |		128 букв |		Success	 |Error |		fail |		ID_4 |	
7 |		Ввести 129 латинских букв	 |	 |		129 букв |		Error	 |		pass	 |	
8 |		Ввести имя и добавить цифры в конце	 |	 |		Maksim123 |		Success	 |		pass |	 |		
9 |		Ввести имя и добавить цифры в начале |		 |		123Maksim |		Success	 |		pass |	 |		
10 |		Добавить в имя разрешенные спецсимволы |	 |			M a-k_s.im |		Success	 |		pass |	 |		
11 |		Внести только цифры	 |	 |		345678 |		Success	 |		pass	 |	 |	


