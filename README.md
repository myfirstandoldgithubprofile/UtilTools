# UtilTools
Some tools that I use in my iOS apps

H3 CryptographUtil

```objective-c
NSString *keyString = @"YOUR_KEY";
NSString *dataString = @"YOUR_DATA;"
NSString *hmac = [[NSString alloc] init];
hmac = [CryptographUtil hmacForKeyAndDataWithKey:keyString data:dataString];
```
