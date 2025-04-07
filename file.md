# Pro Camera Kit

## Overview
Our professional camera kit includes everything you need for high-quality photography and videography.

[Info] This kit is perfect for professional photographers and videographers who need reliable, high-quality equipment.

### Features
- 4K video capability
- 24.2MP sensor
- Weather-sealed body
- Dual card slots

[Warning] Always ensure batteries are fully charged before important shoots.

[Code language="javascript" title="Camera Configuration API"]
// Example code for configuring camera settings
const camera = new ProCamera();

camera.configure({
  resolution: '4K',
  frameRate: 60,
  bitDepth: 10,
  colorProfile: 'LOG',
  stabilization: true
});

// Save user presets
function saveUserPreset(name, settings) {
  localStorage.setItem(\`preset_\${name}\`, JSON.stringify(settings));
  return true;
}
[/Code]

[Tabs]
[Tab title="Basic Setup"]
1. Insert battery
2. Insert memory card
3. Attach lens
4. Power on camera
5. Set date and time
[/Tab]
[Tab title="Advanced Setup"]
1. Configure custom buttons
2. Set autofocus parameters
3. Customize picture profiles
4. Configure network settings
5. Calibrate viewfinder
[/Tab]
[Tab title="Accessories"]
- Extra batteries
- Battery grip
- Remote trigger
- Lens filters
- Memory cards
[/Tab]
[/Tabs]

[Image src="https://placehold.co/600x400" caption="Camera body with premium lens attachment" alt="Professional Camera Setup"]

[Video src="https://openvirtualworlds.org/omeka/items/embed/30" poster="https://placehold.co/600x400" caption="Quick start guide video tutorial"]

[FAQ]
[Q] How long does the battery last?
[A] The standard battery provides approximately 4 hours of continuous shooting or around 500 photos. Extended batteries are available that can double this capacity.

[Q] Is this camera weather resistant?
[A] Yes, the camera body is weather-sealed against dust and moisture, allowing for shooting in challenging environmental conditions. However, it is not fully waterproof and should not be submerged.

[Q] What memory cards are compatible?
[A] The camera supports both SD UHS-II and CFexpress Type B cards. For 4K video recording, we recommend using CFexpress cards with minimum write speeds of 400MB/s.
[/FAQ]

## Maintenance
Regular cleaning and maintenance is essential...
