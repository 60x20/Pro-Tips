# Settings for PC (Windows 10)

## On installation

- On installation, Windows prompts the user with configuration questions, these should be answered using a "do not share/store any personal data" policy

## Settings

### System

#### Display

- Night light: Turn on: 20:30 / Turn off : 07.00
- Scale: 125% (keep in mind that this causes some Windows prompts to be blurry)

#### Focus assist

- Focus Assist: Off

#### Power and Sleep

- Screen 10 minutes, Sleep 15 minutes

#### Multitasking

Snap windows: Off

#### Shared experience

- Nearby Sharing: Off
- Share Across Devices: Off

#### Clipboard

- Clipboard history: On

#### About

- Advanced System Settings (Related settings / Top right)
  - Advanced => Performance => Settings => Visual Effects
    - Show thumbnails instead of icons
    - Show window contents while dragging
    - Smooth edges of screen fonts
  - Remote: Off

### Bluetooth

- More Bluetooth options
  - Discovery: Off
  - Show the Bluetooth icon: On

### Devices

#### Mouse

- Select your primary button: Right
- Cursor speed: 15
- Roll the mouse wheel to scroll: Multiple lines at a time
- Scroll each time: 5
- Scroll inactive windows: On

#### Typing

- Autocorrect: Off
- Advanced keyboard settings => Input language hot keys: None / Not assigned
  - ![Advanced keyboard settings](/assets/settings/advanced-keyboard-settings.png)

### Network and Internet

#### Status => Properties

- Network profile: Public

### Personalization

#### Colors

- Theme: Dark
  - If Windows is not activated: RegEdit => Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Themes\Personalize
    - AppsUseLightTheme: 0
    - SystemUsesLightTheme: 0
    - ![RegEdit for theme](/assets/settings/RegEdit-for-theme.png)

#### Taskbar

- Auto hide task bar: On
  - If Windows is not activated: RegEdit => Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3
    - ![RegEdit for taskbar](/assets/settings/RegEdit-for-taskbar.png)

### Apps

#### Apps and features

- Remove unused apps

#### Default apps

- Web browser: Opera

#### Startup

- Opera / Clock / VSCode

### Time and Language

#### Date and Time

- Set time automatically: On
- Time zone: Istanbul

#### Region

- Country: United States
- Regional Format: English (US)
- Change data formats:
  - First day of week: Monday
  - Date Format: day/month/year
  - ![data format](/assets/settings/customize-format.png)

#### Language

- Full English
- Preferred Languages: Turkish as a second language

#### Speech

- Full English

### Gaming

#### Xbox Game bar

- Off

#### Game mode

- Off

### Ease of access

#### Display

- Make text bigger: 120%
- Make everything bigger: 125%
- Show animations: Off
- Show desktop background image: Off

#### Mouse pointer

- Size: 1
- Touch feedback: Off

#### Text Cursor

- indicator: Off
- Change text cursor thickness: 1

#### Magnifier

- Smooth edges of images and text: Off

#### Color filters

- Off
- Allow the shortcut: Off

#### Narrator

- Off
- Allow the shortcut: Off

#### Audio

- Mono: On

#### Keyboard

- Sticky keys: Off
  - Shortcut : Off
- Toggle keys: Off
  - Shortcut: Off
- Filter keys: Off
  - Shortcut: Off

### Search

#### Permission and History

- Everything: Off

### Privacy

#### General

- Everything: Off

#### Inking & Typing Personalization

- Off

#### Diagnostics & Feedback

- Diagnostic Data: Only required data
- Everything: Off
- Feedback frequency: Never

#### Activity History

- Off

#### Location

- Everything: Off

#### Camera

- Everything: Off

#### Microphone

- Everything: Off

#### Voice Activation

- Everything: Off

## Control Panel

- View by: Large Icons

### Ease of Access Center

- Always read this section: Off
- Always scan this section: Off

#### Make the computer easier to see

- High Contrast
  - Shortcut: Off
  - Everything: Off

#### Make the mouse easier to use

- Mouse Keys: On
- Set up Mouse Keys:
  - Shortcut: Off
    - Everything: Off
  - CTRL to speed up / Shift to slow down: On
  - Use Mouse Keys when Num Lock is: Off
  - Display the icon on Taskbar: Off

#### Make touch and tablets easier to use

- None

### File Explorer Options

#### General

- Browse Folders: Open each folder in its own window
- Click items as follows: Single-click to open an item
  - Underline icon titles only when I point at them

#### View

- Display the full path: On
- Show hidden files
- Hide empty drives: Off
- Hide extensions: Off
- Use checkboxes: On
- Show all folders: On

### Internet Options => Advanced

<!-- TBD -->

### Keyboard properties

- Repeat Delay: 3/4
- Repeat Rate: Maximum
- Cursor blink rate: 8/12

### Mouse properties

#### Buttons

- Switch Primary and Secondary: On

#### Wheel

- Vertical/Horizontal Scrolling: 3

### Power Options

- Power Saver
  - Change plan settings => Wireless adapter settings => maximum performance

### programs and features

- Remove unused apps

### region

- Additional settings => Time:
  - Short Time: H:mm
  - Long Time: H:mm:ss

### Security and Maintenance

- Change User Account Control settings: 3 (Do not dim my desktop)

### Sound

- Playback => Default Device => properties => enhancements:
  - Low frequency protection: On
  - Loudness equalization: On

