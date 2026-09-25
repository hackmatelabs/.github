# hackmate labs

tools for building and maintaining hackintoshes, made because doing this by hand sucks.

## the repos

- [hackmate](https://github.com/hackmatelabs/hackmate) automates the whole process of building a bootable opencore hackintosh usb. no manual config.plist editing, no hunting down kexts, no macrecovery commands.
- [hackmate-goldengate](https://github.com/hackmatelabs/hackmate-goldengate) booting real macos 27 on intel via qemu/tcg, proven on a thinkpad t480s.
- [hackmate-core](https://github.com/hackmatelabs/hackmate-core) a branded graphical boot picker for opencore, opencanopy theme plus a config profile. not a fork, opencore itself stays unmodified.
- [hackmate-hwdb](https://github.com/hackmatelabs/hackmate-hwdb) a hardware database built from real user logs, used to make hackmate smarter over time.
- [hackmate-bot](https://github.com/riftaway7-code/hackmate-bot) a discord bot for querying the hardware database live.

## why

most hackintosh tooling assumes you already know what you're doing. hackmate is built for people who don't want to spend a week reading forum threads just to get macos booting.

## contributing

issues and prs are welcome across every repo. logs submitted through hackmate feed straight into hackmate-hwdb automatically.
