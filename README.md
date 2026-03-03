# Expansion Tile Widget Demo
ExpansionTile is a Flutter widget that creates a collapsible section with a header that expands to reveal content when tapped.
### Screenshot
![collapsed](<Screenshot 2026-03-03 092812.png>) 
![Expanded](<Screenshot 2026-03-03 092931.png>)
Collapsed and Expanded states
### How to Run
1. git clone https://github.com/YOUR_USERNAME/expansion-tile-demo.git
2. cd expansion-tile-demo
3. flutter pub get
4. flutter run -d chrome
Or run on Android/iOS emulator: flutter run

## Three Key Attributes
1. initiallyExpanded (bool, default: false)
Controls whether the tile starts expanded or collapsed. when default is set to false the tile starts collapsed so you can only see the title.
2. backgroundColor (Color?, default: null)
Sets the background color when expanded. 
3. childrenPadding (EdgeInsetsGeometry?, default: EdgeInsets.zero)
Adds spacing around the expanded content helps to make it look not cramped. Essential for a clean, professional appearance.

### Use Case
This demo shows "what is flutter" question with an FAQ section style. A common feature seen in help pages, product sites, and support portals where users tap questions to see answers.