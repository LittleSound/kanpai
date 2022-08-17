# Changelog

## Unreleased

No unreleased changes.

## 0.10.3

No unreleased changes.

## 0.10.2

- fix: remove default pending content
- fix: repeat log
- fix(ChangeLog): Change log not added correctly
- Pin dependency joycon to 3.1.1 (#21)
- Refactor
- Remove global config
- Update dependency marked to v4.0.12 (#19)
- Update dependency typescript to v4.5.5 (#18)
- Update dependency tsup to v5.11.11 (#13)
- Update dependency marked to v4.0.10 (#17)
- Release 0.10.1
- Support `https` git url
- Update readme again
- Update readme
- Update readme
- Fix workflow
- Release 0.10.0
- Update release.yml
- Update release.yml
- Create release.yml
- Pin dependencies (#14)
- Tweaks
- Generate default changelog from commit messages
- Add `release` command
- Release 0.9.9
- Missing changelog body on GitHub Releases
- Release 0.9.8
- Add `gh-release` command
- Pin dependencies (#11)
- Add renovate.json (#10)
- Release 0.9.7
- Fix first release again
- Release 0.9.6
- Fix changelog heading
- Release 0.9.5
- Fix first release
- Release 0.9.4
- Remove `v` prefix from version number in CHANGELOG
- Release v0.9.3
- Make sure git push tags too
- Release v0.9.2
- Replace `%s` in commit message
- Release v%s
- Handle `## Unrelease` title in CHANGELOG.md
- Require version to be specified
- Release v0.9.0
- Tweaks
- Update pkg bin
- Set default config
- Tweaks
- Revive this project, migrate to TypeScript
- -> v0.8.2
- Allow to publish on any branch
- -> v0.8.1
- tweak default version message
- -> v0.8.0
- boost git check time
- use ensure-git
- update readme
- -> v0.7.2
- add default npm script for testing
- -> v0.7.1
- add yarn.lock
- throw as version is not valid
- add options to skip test
- -> v0.7.0
- fix config
- remove testen for now
- fix test script
- -> v0.6.0
- add next option
- allow npm publish with tag
- -> v0.5.3
- fix xo
- display changelog
- update readme
- -> v0.5.2
- fix xo config
- fix xo
- fix missing
- remove unnesscessary alias
- add config
- 0.5.1
- no need to detect branch
- fix typo
- 0.5.0
- add protip
- prepare git before publish
- 0.4.4
- temp fix git
- 0.4.3
- fix xo
- exit when user kill the current spawned program
- add protip, refer to testen
- 0.4.2
- use cross-spawn, fix spawn enoent on windows
- update readme
- update readme
- add screenshot
- 0.4.1
- new heading style
- 0.4.0
- read config from package.json
- typo
- update readme
- 0.3.0
- improve cli usage
- 0.2.0
- add push-only
- 0.1.11
- shorten the heading
- 0.1.10
- xo
- use current branch
- clean
- 0.1.9
- adapt chars for non-darwin platform
- 0.1.8
- options for custom test script
- 0.1.7
- use fancy-hr
- remove intro
- update readme
- update readme
- update logo
- update format
- add logo
- 0.1.6
- log when push
- 0.1.5
- add screencast
- 0.1.4
- update readme
- 0.1.3
- escape color when done
- 0.1.2
- log when publish
- 0.1.1
- simplify
- 0.0.0-kanpai
- 0.1.0
- 0.0.0
- init## 0.10.1

- Support `HTTPS` git URL.

## 0.10.0

- Move `npm publish` and `kp gh-release` to a standalone command: `kp release`, now running `kp` will only update `package.json`, create git tag and push to GitHub. `kp release` is used to actually publish on npm and create release on GitHub, this step could be automated via CI instead, env variables `GITHUB_TOKEN` and `NPM_TOKEN` are required for this to work.
- Generate default changelog from commit messages.

## 0.9.9

- Missing changelog body on GitHub Releases.

## 0.9.8

- Add `kp gh-release` command to publish a new release on GitHub.
- Migrate this package to esm format.

## 0.9.7

- Fix first release again

## 0.9.6

- Fix changelog heading

## 0.9.5

- Fix first release
- Prepend `## Unreleased` to the top of the changelog

## 0.9.4

- Remove `v` prefix from default version number in CHANGELOG.md

## 0.9.3

- Make sure git push tags too

## 0.9.2

- Replace `%s` in commit message with actual version number.

## 0.9.1

- Require version to be specified to prevent accidentally running `kp`
- Automatically change title `## Unreleased` in `CHANGELOG.md` to actual version `## vx.y.z` when publishing
