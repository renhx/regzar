regzarr
=======

Remote control for REGZA

## Usage

#### Change channel

```
$ regzar channel 3
$ regzar channel prev
$ regzar channel next
```

#### Volume up/down/mute

```
$ regzar volume up
$ regzar volume down
$ regzar volume mute
```

#### Power up/down

```
$ regzar power
```

### Change source

```
$ regzar source #=> toggle dtv, hdmi1, hdmi2, ...
$ regzar source dtv
$ regzar source bs
$ regzar source cs
```

## Settings

See example.regzarrc

```~/.regzarrc
ip: 192.168.xxx.xxx
user: username
pass: password
```

## License

This software is released under the MIT License, see LICENSE.
