```json
{
  "token": "docker",
  "full_token": "docker",
  "tap": "homebrew/cask",
  "name": [
    "Docker Desktop",
    "Docker Community Edition",
    "Docker CE"
  ],
  "desc": "App to build and share containerized applications and microservices",
  "homepage": "https://www.docker.com/products/docker-desktop",
  "url": "https://desktop.docker.com/mac/main/amd64/69879/Docker.dmg",
  "appcast": null,
  "version": "4.1.1,69879",
  "versions": {},
  "installed": null,
  "outdated": false,
  "sha256": "de479dab3ec14041980167c99e1fef966556e43a07a6e68afb500e1c5465b7ec",
  "artifacts": [
    {
      "delete": [
        "/Library/PrivilegedHelperTools/com.docker.vmnetd",
        "/private/var/tmp/com.docker.vmnetd.socket",
        "$(brew --prefix)/bin/docker",
        "$(brew --prefix)/bin/docker-compose",
        "$(brew --prefix)/bin/docker-credential-desktop",
        "$(brew --prefix)/bin/docker-credential-ecr-login",
        "$(brew --prefix)/bin/docker-credential-osxkeychain",
        "$(brew --prefix)/bin/hyperkit",
        "$(brew --prefix)/bin/kubectl",
        "$(brew --prefix)/bin/kubectl.docker",
        "$(brew --prefix)/bin/notary",
        "$(brew --prefix)/bin/vpnkit"
      ],
      "launchctl": [
        "com.docker.helper",
        "com.docker.vmnetd"
      ],
      "quit": "com.docker.docker",
      "signal": {}
    },
    [
      "Docker.app"
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker-compose.bash-completion",
      {
        "target": "$(brew --prefix)/etc/bash_completion.d/docker-compose"
      }
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker.zsh-completion",
      {
        "target": "$(brew --prefix)/share/zsh/site-functions/_docker"
      }
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker.fish-completion",
      {
        "target": "$(brew --prefix)/share/fish/vendor_completions.d/docker.fish"
      }
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker-compose.fish-completion",
      {
        "target": "$(brew --prefix)/share/fish/vendor_completions.d/docker-compose.fish"
      }
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker-compose.zsh-completion",
      {
        "target": "$(brew --prefix)/share/zsh/site-functions/_docker_compose"
      }
    ],
    [
      "/Applications/Docker.app/Contents/Resources/etc/docker.bash-completion",
      {
        "target": "$(brew --prefix)/etc/bash_completion.d/docker"
      }
    ],
    {
      "trash": [
        "$(brew --prefix)/bin/docker-compose.backup",
        "$(brew --prefix)/bin/docker.backup",
        "~/Library/Application Support/Docker Desktop",
        "~/Library/Application Support/com.bugsnag.Bugsnag/com.docker.docker",
        "~/Library/Application Scripts/com.docker.helper",
        "~/Library/Caches/KSCrashReports/Docker",
        "~/Library/Caches/com.docker.docker",
        "~/Library/Caches/com.plausiblelabs.crashreporter.data/com.docker.docker",
        "~/Library/Containers/com.docker.docker",
        "~/Library/Containers/com.docker.helper",
        "~/Library/Group Containers/group.com.docker",
        "~/Library/HTTPStorages/com.docker.docker.binarycookies",
        "~/Library/Preferences/com.docker.docker.plist",
        "~/Library/Preferences/com.electron.docker-frontend.plist",
        "~/Library/Saved Application State/com.electron.docker-frontend.savedState",
        "~/Library/Logs/Docker Desktop"
      ],
      "rmdir": [
        "~/Library/Caches/KSCrashReports",
        "~/Library/Caches/com.plausiblelabs.crashreporter.data"
      ],
      "signal": {}
    }
  ],
  "caveats": null,
  "depends_on": {},
  "conflicts_with": {
    "formula": [
      "docker",
      "docker-completion",
      "docker-compose",
      "docker-compose-completion",
      "docker-credential-helper-ecr",
      "hyperkit",
      "kubernetes-cli"
    ]
  },
  "container": null,
  "auto_updates": true,
  "analytics": {
    "install": {
      "30d": {
        "docker": 19090
      },
      "90d": {
        "docker": 55445
      },
      "365d": {
        "docker": 222208
      }
    }
  },
  "generated_date": "2021-10-22"
}
```