# Study with Ionic
Study for self development to be an Ionic developer.


### Command List
[Capacitor commands link](https://capacitorjs.com/docs/getting-started/with-ionic)

### Some plugins already worked
- [Barcode-scanner](https://github.com/capacitor-community/barcode-scanner)
- [Capacitor resources add](https://github.com/leonardoquevedox/capacitor-resources)

### Ionic Live reload steps-
 - Find your ip address
 - Connect your mobile with same internet
 - And use a cable to connect your phone with pc
 - Run command `ionic cap run android -l --host=192.168.1.100` this is your-ip '192.168.1.100'
 - Wait and see to run your project on your android phone with lively

 [Live reload](https://ionicframework.com/docs/cli/commands/capacitor-run) by capacitor: `ionic cap run android -l --external` and `ionic cap run ios -l --external`

### Issue & Solution
Issue | Solution | Description
------------ | ------------- | -------------
HTTP not workin in Android | [Android api issue of 'http'](https://stackoverflow.com/questions/45940861/android-8-cleartext-http-traffic-not-permitted) | Android updated SDK not allow HTTP requrest for API cause of security purposes its defalut is `false` so you may config as per your need.
