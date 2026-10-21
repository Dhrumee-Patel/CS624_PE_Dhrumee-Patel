# Input
This app does not take any input from the user while it runs. Its input is fixed
data written directly in the source code of App.js: my name (Dhrumee Patel), my
degree program (MSCS), and my school (STC). Each of these strings is placed inside
its own Text component.

# Process
When the app starts, Expo loads App.js and React Native renders the App function
component. The component returns one View that contains three Text components.
StyleSheet.create() defines a style named "container" that is applied to the View:
flex: 1 makes the View fill the whole screen, backgroundColor: 'yellow' sets the
background color, and alignItems and justifyContent set to 'center' place the
text in the middle of the screen both horizontally and vertically. React Native
then converts these components into native UI elements on Android or iOS, or into
HTML elements when running on the web.

# Output
The output is a single screen with a yellow background. My name, degree program,
and school are displayed on three separate lines in the center of the screen.