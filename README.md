# react-native-segmented-button
react native scrolled segmented button

##install
npm install react-native-segmented-button@git@github.com:geordasche/react-native-segmented-button.git#develop --save

##screenshots
![image](https://github.com/geordasche/react-native-segmented-button/blob/master/screenshots/1.gif?raw=true)

##example
     <SegmentedButton
                style={{marginTop:100,}}
                tinyColor="#ccc"
                activeTinyColor="#f62323"
                items={['Segmented1',{text:'Seg2'},{text:'SegmentedButton3'},{text:'Seg Btn4'},{text:'Btn5'},]}
                onSegmentBtnPress={(btn,index)=>{}}
                onSegmentBtnPressedAgain={(btn,index)=>{}}
            />
