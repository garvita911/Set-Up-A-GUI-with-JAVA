# Set-Up-A-GUI-with-JAVA
GUI (Often pronounced "GOO-ee", but actually "Gee-Yuuu-Eye") stands for graphical user interface.
In Java development, you're able to create GUIs for your programs without needing any additional downloads! All you need is the Swing GUI Toolkit import statement in the IDE of your choice,
# Setting Up
In Java development, you're able to create GUIs for your programs without needing any additional downloads! All you need is the Swing GUI Toolkit import statement in the IDE of your choice, and you're able to get started immediately!

A JFrame object with a title, and use methods like .setSize(), .setDefaultCloseOperation, and .setLayout to set up your window screen.
Then, close your program with frame.setVisible(true) to see your interface!

# Components
JFrame is a Swing component that allows you to set up your GUI so it shows up when you run your program. Now, you can customize your GUI with other components to add functionality. Some popular Swing components include:

JButton A clickable button
JCheckBox A box that can be checked/unchecked
JRadioButton A radio button (usually in groups)
JToggleButton A button that stays pressed
JComboBox A drop-down list (like a select box)
JTextField A single-line text input

Then , use the .add() to add these components to the frame, since we've only initialized them above.
Then, add functionality to your button by adding a simple action:

button.addActionListener(e -> {
    String name = textField.getText();
    label.setText("Hello, " + name + "!");
});
