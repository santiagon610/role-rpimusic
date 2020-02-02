# Raspberry Pi Music Player

The purpose of this role is to turn a Raspberry Pi with a default load of Raspbian into a music player. My initial use case was to provide on-hold music to my PBX customers, but you can really use it for just about anything.

## Requirements

- Raspbian
- Internet connection to download the packages and music

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: rpi-moh
  roles:
    - role: role-rpimusic
```

## License

Apache 2.0

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
