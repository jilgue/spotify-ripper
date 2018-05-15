```bash

$ docker run --mount type=bind,source="$(pwd)"/Vagrant/Shared/Settings,target=/root/.spotify-ripper \
	--mount type=bind,source=/srv/Music/,target=/music/ -it halfred/spotify-ripper bash

```
