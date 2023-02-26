# virtjs

Work around for [joystick detection in Proton/SDL](https://github.com/ValveSoftware/Proton/issues/5126).

### Prerequisites
Install pkgconf
`sudo apt install pkgconf`

### Usage
1. Clone or download this repo.
2. Navigate to the parent dir and run `make`
3. Verify that a new binary file (named virtjs) has been created inside the repo dir.
4. Run the binary file and give your input device as argument
`sudo ./virtjs /dev/input/by-id/usb-FANATEC_ClubSport_USB_Pedal-event-if00`
5. Open Steam > Settings > Controller > "General Controller Settings"  and verify that a new virtual Xbox 360 controller is detected.
