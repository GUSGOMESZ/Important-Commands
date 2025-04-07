# ECTO 🐢

Here are some important commands related to Ecto !

---

```bash
$ mix ecto.create
```

Creates the database. The database name is defined in the project’s configuration files.

```bash
$ mix ecto.drop
```

Deletes the database.

```bash
$ mix ecto.gen.migration migration_name
```

Generates a new migration.

```bash
$ mix ecto.migrate
```

Runs pending migrations.

```bash
$ mix ecto.rollback
```

Rolls back the last migration.

```bash
$ mix ecto.reset
```

Runs drop, create, and migrate (reset the DB).

```bash
$ mix ecto.setup
```

Runs create, migrate, and run seeds.exs.