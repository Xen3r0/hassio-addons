## 3.16
- Removed git password option as it is no longer usable

## 3.15
- Apply github_tagfilter to dockerhub

## 3.10
- Add dry run mode (test but does not commit)

## 3.9.9
- Add mode
- WARNING : update to supervisor 2022.11 before installing
- Fix : dockerhub_list_size corrected
- New dockerhub_list_size tag for dockerhub
- Look for last 100 elements instead of 10
- New dockerhub_by_date tag for dockerhub
- Nightly tag only for beta
- Use latest lastversion & base images
- Feat: "pause: true" pauses the updates for a specific addon

## 3.*
- Breaking change : new logic. Please read Readme.
- Supports sources from : dockerhub/github,gitlab,bitbucket,pip,hg,sf,website-feed,local,helm_chart,wiki,system,wp

## 2.*
- Add codenotary sign
- Initial build
