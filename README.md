# student-registration-form-using-swing

private void jButton1ActionPerformed(java.awt.event.ActionEvent evt)
{
String fname=jTextField1.getText();
String lname=jTextField2.getText();
String gender=null;
if (jRadioButton1.isSelected())
gender=jRadioButton1.getText();
if (jRadioButton2.isSelected())
gender=jRadioButton2.getText();
if (jRadioButton3.isSelected())
gender=jRadioButton3.getText();
String course=null;
if (jCheckBox1.isSelected())
course=jCheckBox1.getText();
if (jCheckBox2.isSelected())
course=jCheckBox2.getText();
if (jCheckBox3.isSelected())
course=jCheckBox3.getText();
String year=jList1.getSelectedValue();
System.out.println(fname+" "+lname+" "+gender+" "+course+" "+year);}
}
