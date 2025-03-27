# MIX 🩸

Here are some important commands related to Mix !

# Basic Commands

```bash
mix new project_name
```

Creates a new elixir project.

```bash
mix compile
```

Compiles the project.

```bash
mix deps.get
```

Fetches project dependencies.

```bash
mix test
```

Runs tests.

```bash
mix run
```

Executes the project.

```bash
mix format
```

Auto-formats code.

# Ecto (Database) Commands

```bash
mix ecto.create
```

Creates the database. The database name is defined in the project’s configuration files.

```bash
mix ecto.drop
```

Deletes the database.

```bash
mix ecto.gen.migration migration_name
```

Generates a new migration.

```bash
mix ecto.migrate
```

Runs pending migrations.

```bash
mix ecto.rollback
```

Rolls back the last migration.

```bash
mix ecto.reset
```

Runs drop, create, and migrate (reset the DB).

```bash
mix ecto.setup
```

Runs create, migrate, and run seeds.exs.

# Phoenix Commands

```bash
mix phx.new project_name
```

Creates a new Phoenix project.

```bash
mix phx.server
```

Starts the Phoenix web server.

```bash
mix phx.routes
```

Displays all defined routes.