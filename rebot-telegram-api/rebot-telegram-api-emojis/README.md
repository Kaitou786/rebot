# ReBot Emojis

Just provides Emojis to be used by the API, plugins and the Bot itself.

To use an emoji in your plugins, just add it in the pom.xml:

```xml
<dependency>
    <groupId>it.rebase</groupId>
    <artifactId>rebot-telegram-api-emojis</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```


Then use it:


```java
private String message = "Just a simple message with emoji " + Emoji.SMILING_FACE_WITH_OPEN_MOUTH;
```

Check the [list](src/main/java/it/rebase/rebot/plugin/welcome/WelcomeMessagePlugin.java) of available emojis.


### Did you find a bug or do you have a suggestion?
Feel free to raise a [issue](https://github.com/rebase-it/rebot/issues/new) or send a email: just@rebase.it