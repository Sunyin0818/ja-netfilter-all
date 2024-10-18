# Operation guide: 

1. get ja-netfilter.jar 
2. add -javaagent:/path/to/ja-netfilter.jar=jetbrains to your vmoptions
3. use key on page https://jetbra.in/5d84466e31722979266057664941a71893322460

Enjoy it~



## vmoptions details

add these 3 lines to your vmoptions file: (for manual, without any whitespace chars)
modify path to your ja-netfilter.jar file    

```                             bash
--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
-javaagent:D:\Crack\ja-netfilter-all\ja-netfilter.jar=jetbrains
```
