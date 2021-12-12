# React-Native-Rtl-Reshaper
## Support both React & React-Native
By this you could write RTL languages correctly where RTL language is not supported. 
**To all developers who have such problem **

##Installation

**npm package users**
> npm i react-native-rtl-reshaper

**yarn package users**
> yarn add react-native-rtl-reshaper

##Quick Example
```
import {convertRtl} from 'react-native-rtl-reshaper';

<Text>{convertRtl('فروردین')}</Text>
<Text>{convertRtl('اردیبهشت')}</Text>
<Text>{convertRtl('خرداد')}</Text>
...

```
### This is the problem
![54937954-111c9600-4f43-11e9-880c-305c15a180b4](https://user-images.githubusercontent.com/43260748/145704124-d926d997-7192-4b88-ac98-acd45750cda2.jpg)
### This is the final result
![Screenshot_1639294017](https://user-images.githubusercontent.com/43260748/145704177-32888005-eb5a-4473-a96a-765e4cf5b66c.png)
