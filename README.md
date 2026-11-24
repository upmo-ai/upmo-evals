# Upmo evals

Public eval sets for Upmo's knowledge and memory retrieval. The main repo,
[upmo-ai/upmo](https://github.com/upmo-ai/upmo), pins this repo by commit
and runs the sets with `make eval-knowledge` and `make eval-memory`.

## Layout (planned)

- `knowledge/docs/`: about 200 source documents.
- `knowledge/questions.jsonl`: about 90 questions with expected answers.
- `memory/`: a scripted stream of changing facts in the StaleBench form.
- `labels/`: about 100 hand-checked answers used to check the judge.
- `SOURCES.md`: the source URL and license of every document.

## License rules

Every document comes from openly licensed text and keeps its own license,
listed in `SOURCES.md`. Only CC0 and CC-BY sources are accepted for now.
Questions, answers and labels written for this repo are CC0.
