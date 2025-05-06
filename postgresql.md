# POSTGRESQL 🐘

Here are some important commands related to PostgreSQL !

---

```bash
$ pg_config --version
```

Verify the PostgreSQL version installed.

```bash
$ dpkg -l | grep postgresql
```

Verify if Postgresql or related packages are installed.

```bash
$ sudo service postgresql start
```

Start the PostgreSQL service on Linux systems that use systemd or SysV init.

```bash
$ sudo systemctl stop postgresql
```

Stops the PostgreSQL service.
