## 0.6.0 (February 04, 2020)
  - [DOC] added new label to documentation
  - Merge pull request #8 from danielgrabowski/issue_level
  - [FEATURE] added issue_level label to metric

## 0.5.0 (July 19, 2019)
  - [DOC] added new parameter to documentation
  - [FEATURE] added HTTP_PROTO env variable (pull request #7 from killmeplz/patch-1)

## 0.4.1 (May 16, 2019)
  - [TASK] Merge pull request #4 from marcindulak/issue-2
  - [BUGFIX] set 'issue_logger' to 'unknown' if NULL
  - [DOC] fixed formatting, added docker hub link

## 0.4.0 (March 04, 2019)
  - [TASK] composer is now updated in the image to enable auto builds
  - [DOC] removed unnecessary timestamps

## 0.3.1 (March 01, 2019)
  - [BUGFIX] removed unnecessary timestamps

## 0.3.0 (March 01, 2019)
  - [FEATURE] #1 provide the package as ready-to-use docker image
  - [DOC] updated output
  - [DOC] fixed typo
  - [DOC] added example output

## 0.2.0 (February 27, 2019)
  - [TASK] renamed metric from sentry_project_open_issues to sentry_open_issue_events
  - [FEATURE] added some more label values
  - [TASK] added ext-json to requirements list

## 0.1.2 (February 27, 2019)
  - [BUGFIX] renamed collection/metric
  - [BUGFIX] of course, issue counts can go down again, so gauges, not counters

## 0.1.1 (February 27, 2019)
  - [DOC] fixed sentry host

## 0.1.0 (February 27, 2019)
  - merge branch 'master' of github.com:ujamii/prometheus-sentry-exporter
  - Initial commit

