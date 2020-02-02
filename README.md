# Raspberry Pi Music Player

The purpose of this role is to turn a Raspberry Pi with a default load of Raspbian into a music player. My initial use case was to provide on-hold music to my PBX customers, but you can really use it for an unattended music player.

## Requirements

- Raspbian
- Internet connection to download the packages and music

## Role Variables

Runtime vars:

- `install_music`: boolean. If defined, will install a sample track to the music directory destination node.

[Defaulted](defaults/main.yml) vars:

- `tracks_directory`: string. Path in which tracks to be played will be located.
- `scripts_directory`: string. Path in which helper scripts will be placed.
- `logs_directory`: string. Path in which logs will be generated.
- `musicplayer_owner`: string. User that will take ownership of the music player service.
- `musicplayer_group`: string. A group in which `musicplayer_owner` is a member.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: rpi-moh
  roles:
    - role: role-rpimusic
```

## License

[Apache 2.0](LICENSE)

## Author Information

Nicholas Santiago, [HLV Technologies LLC](https://www.hlvpa.com)
