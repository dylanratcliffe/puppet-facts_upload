
# facts_upload

Triggers an upload of the latest facts. This is important if you are running in cached catalog mode and need node facts to be up to date.

### Tasks

#### `facts_upload`

Runs `puppet facts upload`, a feature added in [PUP-8232](https://tickets.puppetlabs.com/browse/PUP-8232) to allow updating of facts on demand, most useful when running agents in cached catalog mode.
