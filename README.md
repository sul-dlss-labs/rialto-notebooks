# rialto-notebooks

This repository contains some notebooks for interacting with the [Rialto] database.

First create a `.env` file containing the password for the read-only `analyst` user. A member of the infrastructure or ops team can get you this. The `.env` file should look like this:

```
DB_PASSWORD=THE_REAL_PASSWORD_HERE
```

To run the notebooks them you will need to install [uv] and then:

```shell
$ uv run jupyter lab
```

[Rialto]: https://github.com/sul-dlss/rialto-airflow
[uv]: https://docs.astral.sh/uv/getting-started/installation/
