# MessageBox
# Create By Mr: Khamphay CS2
1. Install Font Phetsarath OT.
2. Install Version of Framework >=2.0.
3. Drap the file 'MyMessageBox.dll' to the Reference of your project
            Or 
    Add Reference and choose the file 'MyMessageBox.dll'.
4. How to use:
    Example:
      -C#: 
          using MyMessageBox;

          MyMessage.Show("ລາຍລະອຽດ","ຊື່ຟອມ", MessageBoxButton.YesNo, MessageIcon.Information);
          MyMessage.Show("ລາຍລະອຽດ","ຊື່ຟອມ","Phetsarath OT", 12, MessageBoxButton.YesNo, MessageIcon.Information);


      -VB.Net: 
          import MyMessageBox

          MyMessage.Show("ລາຍລະອຽດ","ຊື່ຟອມ" MessageBoxButton.YesNo, MessageIcon.Information)
          MyMessage.Show("ລາຍລະອຽດ","ຊື່ຟອມ","Phetsarath OT", 12, MessageBoxButton.YesNo, MessageIcon.Information)
