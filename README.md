# neumorphism
--Neumorphism for OpenHarmony.

## Download & Install

```npm install @ohos/neulib```

## Import all components at once

```ets
import {Theme,strTheme,button,strButton,buttons,strButtons,avatar,strAvatar,dropdown} from '@ohos/neulib'
import {strDropdown,input,strInput,card,strCard,carousel,strCarousel,progress,strProgress} from '@ohos/neulib'
import {alert,strAlert,label,strLabel,navbar,strNavbar,pagination,strPagination,radio} from '@ohos/neulib'
import {switcher,strRadio,strSwitcher,checkbox,strCheckbox} from '@ohos/neulib'
```

# Theme

Import:
```ets
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
@State theme: strTheme.Model = new strTheme.Model();

build(){
    Theme({ theme: this.theme })
}
```

# Alert

Import:
```ets
import {alert,strAlert} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
alert: strAlert.Model = new strAlert.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    alert({alert: this.alert, theme: this.theme})
}
```

# Avatar

Import:
```ets
import {avatar,strAlert} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
avatar: strAvatar.Model = new strAvatar.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    avatar({avatar: this.avatar, theme: this.theme})
}
```

# Button

Import:
```ets
import {button,strButton} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
button: strButton.Model = new strButton.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    button({button: this.button, theme: this.theme})
}
```

# Buttons

Import:
```ets
import {buttons,strButtons} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
buttons: strButtons.Model = new strButtons.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    buttons({buttons: this.buttons, theme: this.theme})
}
```

# Card

Import:
```ets
import {card,strCard} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
card: strCard.Model = new strCard.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    card({card: this.card, theme: this.theme})
}
```

# Checkbox

Import:
```ets
import {checkbox,strCheckbox} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
checkbox: strCheckbox.Model = new strCheckbox.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    checkbox({checkbox: this.checkbox, theme: this.theme})
}
```

# Dropdown

Import:
```ets
import {dropdown,strDropdown} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
dropdown: strDropdown.Model = new strDropdown.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    dropdown({dropdown: this.dropdown, theme: this.theme})
}
```

# Form

Import:
```ets
@State theme: strTheme.Model = new strTheme.Model();
import {input,strInput} from '@ohos/neulib'
import {button,strButton} from '@ohos/neulib'
```

Usage:
```ets

build(){
    Flex({ direction: FlexDirection.Column, justifyContent: FlexAlign.Center, alignItems: ItemAlign.Center }) {
      input({ input: this.emailInput, theme: this.theme })
      input({ input: this.passwordInput, theme: this.theme })
      Row() {
        button({ button: this.submit, theme: this.theme })
        button({ button: this.reset, theme: this.theme })
      }
    }
    .backgroundColor(this.theme.getBackgroundColor())
    .width('750px')
    .height('700px')
    .borderRadius('50px')
    .shadow({ radius: this.theme.getShadowRadius(),
      color: this.theme.getDownShadow()})
}
```

# Input

Import:
```ets
import {input,strInput} from '@ohos/neulib'
@State import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
input: strInput.Model = new strInput.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    input({input: this.input, theme: this.theme})
}
```

# Label

Import:
```ets
import {label,strLabel} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
label: strLabel.Model = new strLabel.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    label({label: this.label, theme: this.theme})
}
```

# Navbar

Import:
```ets
import {navbar,strNavbar} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
navbar: strNavbar.Model = new strNavbar.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    navbar({navbar: this.navbar, theme: this.theme})
}
```

# Pagination

Import:
```ets
import {pagination,strPagination} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
pagination: strPagination.Model = new strPagination.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    pagination({pagination: this.pagination, theme: this.theme})
}
```

# Progress

Import:
```ets
import {progress,strProgress} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
progress: strProgress.Model = new strProgress.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    progress({progress: this.progress, theme: this.theme})
}
```

# Radio

Import:
```ets
import {radio,strRadio} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
radio: strRadio.Model = new strRadio.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    radio({radio: this.radio, theme: this.theme})
}
```

# Switcher

Import:
```ets
import {switcher,strSwitcher} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
switcher: strSwitcher.Model = new strSwitcher.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    switcher({switcher: this.switcher, theme: this.theme})
}
```

# Carousel

Import:
```ets
import {carousel,strCarousel} from '@ohos/neulib'
import {Theme,strTheme} from '@ohos/neulib'
```

Usage:
```ets
carousel: strCarousel.Model = new strCarousel.Model();
@State theme: strTheme.Model = new strTheme.Model();

build(){
    caousel({carousel: this.carousel, theme: this.theme})
}
```


## Compatibility

Supports OpenHarmony API version 9

## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://github.com/Applib-OpenHarmony/NeumorphismNPM-ETS/issues) to us. Of course, we also welcome you to send us [PR](https://github.com/Applib-OpenHarmony/NeumorphismNPM-ETS/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/Neumorphism/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

Design by : Vivek Choudhary and Sourav

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://github.com/Applib-OpenHarmony/Neumorphism-NPM">Neumorphism-JS</a>




