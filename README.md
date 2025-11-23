# coldboot

As simple a flake-based Rust project I could muster, basically no batteries included but enough to start hacking.

```
nix develop

cargo run
```

Some notes:
* I use the `rust-overlay` at the moment
* `nixfmt-tree` is the nix formatter of choice
* There's some vscode settings assuming you're using `nixEnvSelector`, I'm not really a `direnv` guy

My new favorite way to start a project the moment you're struck with inspiration is with the `gh` CLI

```
# in the ~/sources dir or whenever you want to clone down the new repo
gh repo create NEW_PROJECT_NAME --template treyfortmuller/coldboot --public --clone
```

Replace `--public` with `--private` flag if you want the new project to be a private repo.

You can also literally just run

```
gh repo create
```

And let it prompt you through an interactive setup, then you just have to remember `treyfortmuller/coldboot` as the name of the template to clone down from.
