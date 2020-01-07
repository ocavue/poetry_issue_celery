# poetry_issue_celery

```
bash> git clone https://github.com/ocavue/poetry_issue_celery.git
bash> cd poetry_issue_celery
bash> docker run --rm -it -v $(pwd):/project python:3.5 bash
docker> pip3 install poetry
docker> cd /project
docker> poetry install
[SolverProblemError]
Because poetry-issue-celery depends on celery (*) which doesn't match any versions, version solving failed.
```
