```
IRCg2 @target=1 @messageID=1 @from=Minecraftchest1 @channel=#Example @message="(This is an example message.)" /endmsg/
```
`IRCg2` Specfies that the message is using the IRCg2 message spec.
`@target=1` Specfies that the message was sent using folowing compability target 1 specs.
`@from=Minecraftchest1` Is the nickname of the user that sent the message.
`@channel=#Example` Is the channel the message was sent to.
`@message='(This is an example message.)"` Contains the message. The `"( )"` is used to show that the full string is the value for the `@message` tag.
`/endmsg/` Marks the end of the message.
