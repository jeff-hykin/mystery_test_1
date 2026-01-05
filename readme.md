
```sh
sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/b0f76b1940d9fd86f4550b3953cce3b74ed72f2e/install")
sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/refs/heads/master/install")
sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/refs/heads/master/install") --help
sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/refs/heads/master/install") --non-interactive --no-env-setup
```
<!-- sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/$(git rev-parse HEAD)/install") -->
<!-- sh <(curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/27d6ad5fb41a4199e947a98ac306d310ef0e23a3/install") -->
<!-- curl -fsSL 'https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/refs/heads/master/install' | sh -s -- < /dev/tty -->
<!-- curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/$(git rev-parse HEAD)/install" | sh -s -- < /dev/tty
curl -fsSL "https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/$(git rev-parse HEAD)$/install" | sh -s -- < /dev/tty

git_current_commit_hash
curl -fsSL 'https://raw.githubusercontent.com/jeff-hykin/mystery_test_1/refs/heads/master/install' \
   -->
