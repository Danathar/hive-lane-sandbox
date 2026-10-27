# hive-lane-sandbox

Throwaway repository for exercising the Hive v6 serialized merge lane
(`merge_strategy: hive-serialized`) for
[hivecommons/hive#7563](https://github.com/hivecommons/hive/issues/7563).

Its one required check, `test`, is steered by files in the tree: `SLOW` and
`SLOWER` delay it, `FAIL` fails it. Pull requests here are test fixtures.
Safe to delete once the evidence is posted.
