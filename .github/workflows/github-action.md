## Github Action
- https://github.com/marketplace/actions/github-tag


**Note:** you can even create `Github Release` by using `ncipollo/release-action@v1` this action as you 
can see in documentation and "YES" it is a seperate github action. Just used here to show release can 
be made by different version of tags.

## Compare previous tags:
- navigate to actions
- open pipeline
- open `tagging` pipeline
- see logs
- once action is build you can see in pipeline that new `tag` is generated based on on previous tag:

`e.g:`
- https://github.com/KhizerRehan/ci-cd/compare/v0.0.1-action-tagging.0...v0.0.1-action-tagging.1