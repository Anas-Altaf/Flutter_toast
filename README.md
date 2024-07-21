# flutter_toast

A Custom Toast Message Demo

## Getting Started

+ add fluttertaost package
  ```flutter pub add fluttertoast```
+ create a file custom_toast
+ paste the flutter_toast.dart code in that file from this repo
+ Import ```import 'custom_toast.dart';```
### Usage
+ Add
 ```bash
   @override
  void initState() {
    super.initState();
    ToastUtil.init(context);
  }
  //Usage in a Function
    ToastUtil.showErrorToast('Current Count : $_counter');
   ```
# Credits
+ [Anas-Altaf](https://github.com/Anas-Altaf)
- Thanks for using.