# React Native Tabbar Interaction

Beautiful Tabbar Interaction with Sliding Inset FABs,
made with React Native.



<img src="https://cdn.dribbble.com/users/1233499/screenshots/4844696/preview.gif" >


# Installation
`npm i mindinventory/react-native-tab-bar-interaction`

Android: `react-native run-android`

iPhone: `react-native run-ios`


# Usage

```js

import TabBar from "react-native-tab-bar-interaction";
...
  render() {
      return (
          <TabBar>
            <TabBar.Item
                icon={require('./tab1.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab1"
                screenBackgroundColor={{ backgroundColor: '#008080' }}
            >
              <View>
                  {/*Page Content*/}
              </View>
            </TabBar.Item>
            <TabBar.Item
                icon={require('./tab2.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab2"
                screenBackgroundColor={{ backgroundColor: '#F08080' }}
            >
                <View>
                    {/*Page Content*/}
                </View>
            </TabBar.Item>
            <TabBar.Item
                icon={require('./tab3.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab3"
                screenBackgroundColor={{ backgroundColor: '#485d72' }}
            >
              <View>
                  {/*Page Content*/}
              </View>
            </TabBar.Item>
          </TabBar>
      );
    }
```

## Component props

| prop | value | required/optional | description |
| --- | --- | --- | --- |
| icon | image source | required | the icon when item is not focus |
| selectedIcon | image source | required | the icon when item is focus |
| title | string | required | title of item |
| screenBackgroundColor | string | required | background color of tab |

## Dependencies

* `react-native-svg`
