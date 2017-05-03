# ansible-ganglia
This can be used to install ganglia in client nodes in one go.

To get started, clone this repo, and follow the given steps

1. Add a `all` file just like `all.example`
2. Add a `clients` file just like `client.example`.
3. If you have changed the `group_name` in clients file, remember to change it in `main.yml` as well.
4. Run `ansible-playbook main.yml -i clients`
