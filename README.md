## π₯ PROJECT μκ°

2019λ 1νκΈ° μλ°νλ‘κ·Έλλ°μ€μ΅ κ°μ κΈ°λ§ ν νλ‘μ νΈ μ μ

> JAVAλ₯Ό μ΄μ©ν΄ λ§λ€μ΄μ§ νλ‘κ·Έλ¨μ κ΅¬νν΄ λ³΄λ©° μ¬ν νμ΅μ νκ³ μ νλ‘μ νΈμ μ°Έμ¬νκ² λμλ€. JAVAλ₯Ό μ¬μ©νμ¬ μ¬λ¬ νλ‘κ·Έλ¨μ λ§λ€ μ μλλ°, κ·Έμ€μμλ νκ΅μμ κ°μ₯ μ¬μ©μ΄ λ§μ΄ λ  μ±μ  κ΄λ¦¬ νλ‘κ·Έλ¨μ κ΅¬νν΄ λ³΄μλ€. νμμ νλ², μ΄λ¦, κ³Όλͺ©λ³ μ±μ μ μλ ₯ν ν μΆκ° λ²νΌμ λλ₯Ό κ²½μ°μ μμ°¨μ μΌλ‘ μ λ³΄κ° μλ ₯λλλ‘ κ΅¬ννμλ€.

ποΈ **μμκΈ°κ°** : 2019. 06.

π¨βπ» **ν¬μμΈμ** : 1λͺ

π **μ£Όμμλ¬΄** 

- κΈ°ν λ° μ€κ³
- κ°λ°

π± **μ€ν¬ λ° μ¬μ©ν΄**

`Java` `Eclipse`

<br>

## ποΈ INFO


1. μ΅μ΄ μ€ν νλ©΄

![init](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d7e88bbf-388d-441d-9ee7-d476e3c04710/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210727%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210727T071250Z&X-Amz-Expires=86400&X-Amz-Signature=5cb254617bb87519be9f950bc025635f2c9644b32454851b5ca5480883edfa2f&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

2. μ±μ  μλ ₯ ν μΆκ° λ²νΌ λλ μ λ

![add](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e1c48b1b-74f7-44ba-9899-449cbbf7551a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210727%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210727T071423Z&X-Amz-Expires=86400&X-Amz-Signature=88beb873e526f9605546d0613e545d7784a8046f53cf1d8a8d09dcb0937056b0&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

3. μ­μ  ν­λͺ© μ ν ν μ­μ  λ²νΌ λλ μ λ

![delete](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8f1b903a-f726-4a9b-b7d8-29064ac17a14/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210727%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210727T071443Z&X-Amz-Expires=86400&X-Amz-Signature=6b9183aa042d15329005fcdac3f283741cd2b317d8048cd2d45420f512c685e5&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

<br>

## βοΈ CODE

νλ‘κ·Έλ¨μ μ€ννμ λ κ°μ₯ μ΄κΈ° νλ©΄μλ μλ¬΄κ²λ λ¨μ§ μκ² νλ€. λ§¨ μμ νλ², μ΄λ¦, JAVA, Python, C++μ΄λΌλ ν€λλ₯Ό λ£μ΄ μ λ³΄λ₯Ό μλ ₯νμμ λ κ΅¬λΆμ΄ λ  μ μλλ‘ νμλ€. μ€ν μ°½ μλ¨μλ βμ±μ  κ΄λ¦¬ νλ‘κ·Έλ¨βμ΄λΌλ λ¬Έμκ° λ° μ μλλ‘ νμμΌλ©°, μ°½ ν¬κΈ°λ `500*400`μΌλ‘ μ€μ νμλ€.

	JFrame frame = new JFrame("μ±μ  κ΄λ¦¬ νλ‘κ·Έλ¨");
		setSize(500, 400);
		String header[] = {"νλ²","μ΄λ¦","JAVA","Python","C++"};
		String contents[][] = {};

`DefaultTableModel`μ΄λΌλ κ°λμ μ¬μ©νμλλ°, μ΄ ν΄λμ€λ₯Ό μ¬μ©νλ©΄ νμ΄λΈμ ν λ¨μλ‘ μ°κ±°λ μ­μ νλ κ²μ΄ μ©μ΄ν΄μ§λ€. `JTable` κ°μ²΄ μμ± μ λ¦¬λͺ¨μ»¨ μ­ν μ νλ κ²κ³Ό κ°λ€. `DefaultTableModel` κ°μ²΄λ₯Ό μμ±νλ©° `JTable`μ λ°μ΄ν°λ₯Ό μ?κ²¨ μ μ₯νλ€.

	DefaultTableModel model = new DefaultTableModel(contents,header);
		JTable table = new JTable(model);
		JScrollPane scrollpane = new JScrollPane(table);

μ΄κΈ° νλ©΄μ΄ λ¬ νμλ μ λ³΄λ₯Ό μλ ₯ν΄μΌ νλλ°, κ·Έ μλ ₯μ μν΄ `JTextField`λ₯Ό μ¬μ©νμ¬ κ΅¬ννμλ€. `JTextField()` κ΄νΈ μμλ μΉΈ ν¬κΈ°λ₯Ό μ§μ ν΄ μ£Όμλ€. `TextField`μμ μλ ₯λ°μ λ°μ΄ν°λ₯Ό λ°°μ΄μλ€ μ μ₯νμ¬ `addRow()` λ©μλλ‘ μλ ₯ν΄ μ£Όμλ€.

	JTextField studentID = new JTextField(5);
		JTextField nameField = new JTextField(5);
		JTextField subject1 = new JTextField(3);
                    .
                    .
                    inputStr[3] = subject2.getText();
		inputStr[4] = subject3.getText();
		model.addRow(inputStr);

λͺ¨λ  μ λ³΄ μλ ₯μ΄ μλ£λ νμλ μ λ³΄λ₯Ό μΆκ°ν  μ μμ΄μΌ νκΈ° λλ¬Έμ κ·Έ μ­ν μ νλ λ²νΌ κΈ°λ₯μ κ΅¬ννμλ€. μΆκ°μ μ­μ  κΈ°λ₯μ ν  μ μλλ‘ νμμΌλ©°, κ΅¬λΆμ΄ μ½κ² μκΉμ μ§μ νμλ€. `ActionListener`λ₯Ό ν΅ν΄ λ²νΌμ΄ μλν  μ μλλ‘ νμλ€. `String` λ°°μ΄μ ν΅ν΄ κ° μΉΈμμ μλ ₯λ μ λ³΄λ₯Ό λ°°μ΄μλ€ μ μ₯ν  μ μκ² νλ€.
`JTable` ν΄λμ€μ λ©μλ μ€ `getSelectedRow()`κ° μλλ°, μ΄λ₯Ό μ¬μ©ν΄ νμ μ νν΄ μ­μ ν  μ μλλ‘ νμλ€. λ§μ½ μ νλ νμ΄ μμ κ²½μ°μλ β1κ°μ λκ²¨ μ£Όλλ‘ μ€μ νμλ€.


		JButton addBtn = new JButton("μΆκ°");
		addBtn.setBackground(Color.YELLOW);      // λ²νΌ μ μ§μ 
		addBtn.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent e) {
				String inputStr[] = new String[5];
				inputStr[0] = studentID.getText();
		.
                    .
                    .
			public void actionPerformed(ActionEvent e) {
				if(table.getSelectedRow() == -1)
				{
					return;
				}
				else
				{
					model.removeRow(table.getSelectedRow());
				}
			}


λ§μ§λ§μΌλ‘ `BorderLayout`μ ν΅ν΄ λ μ΄μμμ μ€μ ν΄ μ£Όμλ€. `panel`μ λ°©ν₯μ μλ ₯ μ°½μ μμΉκ° λ°λλ©°, `scrollpane`μ μ λ³΄λ₯Ό λμ°λ κ³΅κ°μ μμΉλ₯Ό λ»νλ€.

		frame.add(scrollpane, BorderLayout.CENTER);
		frame.add(panel, BorderLayout.SOUTH);

