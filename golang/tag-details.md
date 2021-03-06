<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `golang`

-	[`golang:1.4.3`](#golang143)
-	[`golang:1.4`](#golang14)
-	[`golang:1.4.3-onbuild`](#golang143-onbuild)
-	[`golang:1.4-onbuild`](#golang14-onbuild)
-	[`golang:1.4.3-cross`](#golang143-cross)
-	[`golang:1.4-cross`](#golang14-cross)
-	[`golang:1.4.3-wheezy`](#golang143-wheezy)
-	[`golang:1.4-wheezy`](#golang14-wheezy)
-	[`golang:1.4.3-alpine`](#golang143-alpine)
-	[`golang:1.4-alpine`](#golang14-alpine)
-	[`golang:1.5.3`](#golang153)
-	[`golang:1.5`](#golang15)
-	[`golang:1`](#golang1)
-	[`golang:latest`](#golanglatest)
-	[`golang:1.5.3-onbuild`](#golang153-onbuild)
-	[`golang:1.5-onbuild`](#golang15-onbuild)
-	[`golang:1-onbuild`](#golang1-onbuild)
-	[`golang:onbuild`](#golangonbuild)
-	[`golang:1.5.3-wheezy`](#golang153-wheezy)
-	[`golang:1.5-wheezy`](#golang15-wheezy)
-	[`golang:1-wheezy`](#golang1-wheezy)
-	[`golang:wheezy`](#golangwheezy)
-	[`golang:1.5.3-alpine`](#golang153-alpine)
-	[`golang:1.5-alpine`](#golang15-alpine)
-	[`golang:1-alpine`](#golang1-alpine)
-	[`golang:alpine`](#golangalpine)
-	[`golang:1.6beta2`](#golang16beta2)
-	[`golang:1.6`](#golang16)
-	[`golang:1.6beta2-onbuild`](#golang16beta2-onbuild)
-	[`golang:1.6-onbuild`](#golang16-onbuild)
-	[`golang:1.6beta2-wheezy`](#golang16beta2-wheezy)
-	[`golang:1.6-wheezy`](#golang16-wheezy)
-	[`golang:1.6beta2-alpine`](#golang16beta2-alpine)
-	[`golang:1.6-alpine`](#golang16-alpine)

## `golang:1.4.3`

```console
$ docker pull library/golang@sha256:d7b341922945bd117b459461a71277cb214695a451dc7c98ddce85e77df71904
```

-	Total Virtual Size: 563.1 MB (563059635 bytes)
-	Total v2 Content-Length: 204.7 MB (204677321 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

## `golang:1.4`

```console
$ docker pull library/golang@sha256:c0d9c308e2c0737c572b5160e76b4c46e78c21ce7011c12df1d68dfb9029516d
```

-	Total Virtual Size: 563.1 MB (563059635 bytes)
-	Total v2 Content-Length: 204.7 MB (204677321 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

## `golang:1.4.3-onbuild`

```console
$ docker pull library/golang@sha256:dd9379c50528ba39e8d43eea4b10c52ce93967a97929df2f49a521a790f03df5
```

-	Total Virtual Size: 563.1 MB (563059635 bytes)
-	Total v2 Content-Length: 204.7 MB (204677613 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

#### `904f841dbdf63765386a964fd00b697d989bc46c64c1074390a6ace440b1c471`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:33 GMT
-	Parent Layer: `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b9bccc2a1be415a1bf7ae0f18bc79ba9b36841561a8a175a6235cf93e6b6047b`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:18:55 GMT

#### `e6c3ac00e9cb7087ec86525ebd700f0d30654d733c7155406514c07772416f40`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:34 GMT
-	Parent Layer: `904f841dbdf63765386a964fd00b697d989bc46c64c1074390a6ace440b1c471`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fd4d3b0d907e977d20cd078655bcb27b8453a10d8e892232cf7ef4f6b24564c8`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Fri, 08 Jan 2016 14:35:34 GMT
-	Parent Layer: `e6c3ac00e9cb7087ec86525ebd700f0d30654d733c7155406514c07772416f40`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a6cf19af16f45dfb9e308fcb39b34023cdc64fca3809609fb5f5f6b6b88ed0fa`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:35 GMT
-	Parent Layer: `fd4d3b0d907e977d20cd078655bcb27b8453a10d8e892232cf7ef4f6b24564c8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f19edbee91d5eb0e78153ff6ec7f794e4243afcba31a0548a6507156462356d2`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Fri, 08 Jan 2016 14:35:35 GMT
-	Parent Layer: `a6cf19af16f45dfb9e308fcb39b34023cdc64fca3809609fb5f5f6b6b88ed0fa`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f88ab180b1abc8b823a4b4eeba6712b136386dfd6fb6152efe6d92868b7b0f3`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Fri, 08 Jan 2016 14:35:36 GMT
-	Parent Layer: `f19edbee91d5eb0e78153ff6ec7f794e4243afcba31a0548a6507156462356d2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.4-onbuild`

```console
$ docker pull library/golang@sha256:75f62d7a330706eb0255d469d9e416e9b7562e4cae2029d4ed4fdcb099537cff
```

-	Total Virtual Size: 563.1 MB (563059635 bytes)
-	Total v2 Content-Length: 204.7 MB (204677613 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

#### `904f841dbdf63765386a964fd00b697d989bc46c64c1074390a6ace440b1c471`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:33 GMT
-	Parent Layer: `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b9bccc2a1be415a1bf7ae0f18bc79ba9b36841561a8a175a6235cf93e6b6047b`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:18:55 GMT

#### `e6c3ac00e9cb7087ec86525ebd700f0d30654d733c7155406514c07772416f40`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:34 GMT
-	Parent Layer: `904f841dbdf63765386a964fd00b697d989bc46c64c1074390a6ace440b1c471`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fd4d3b0d907e977d20cd078655bcb27b8453a10d8e892232cf7ef4f6b24564c8`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Fri, 08 Jan 2016 14:35:34 GMT
-	Parent Layer: `e6c3ac00e9cb7087ec86525ebd700f0d30654d733c7155406514c07772416f40`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a6cf19af16f45dfb9e308fcb39b34023cdc64fca3809609fb5f5f6b6b88ed0fa`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Fri, 08 Jan 2016 14:35:35 GMT
-	Parent Layer: `fd4d3b0d907e977d20cd078655bcb27b8453a10d8e892232cf7ef4f6b24564c8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f19edbee91d5eb0e78153ff6ec7f794e4243afcba31a0548a6507156462356d2`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Fri, 08 Jan 2016 14:35:35 GMT
-	Parent Layer: `a6cf19af16f45dfb9e308fcb39b34023cdc64fca3809609fb5f5f6b6b88ed0fa`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f88ab180b1abc8b823a4b4eeba6712b136386dfd6fb6152efe6d92868b7b0f3`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Fri, 08 Jan 2016 14:35:36 GMT
-	Parent Layer: `f19edbee91d5eb0e78153ff6ec7f794e4243afcba31a0548a6507156462356d2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.4.3-cross`

```console
$ docker pull library/golang@sha256:dadf585af6081b573837e655bf5527646de65faee43a2372380b2d20f9266d54
```

-	Total Virtual Size: 2.4 GB (2384849364 bytes)
-	Total v2 Content-Length: 665.2 MB (665214478 bytes)

### Layers (17)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

#### `7fccb073e3909ab6081588fe730ea332b735e73e1319dc51b443f4073f5d6247`

```dockerfile
ENV GOLANG_CROSSPLATFORMS=darwin/386 darwin/amd64 	dragonfly/386 dragonfly/amd64 	freebsd/386 freebsd/amd64 freebsd/arm 	linux/386 linux/amd64 linux/arm 	nacl/386 nacl/amd64p32 nacl/arm 	netbsd/386 netbsd/amd64 netbsd/arm 	openbsd/386 openbsd/amd64 	plan9/386 plan9/amd64 	solaris/amd64 	windows/386 windows/amd64
```

-	Created: Fri, 08 Jan 2016 14:35:59 GMT
-	Parent Layer: `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e1c1441194fd8016f3825487a30ff5b06ba71981635a4bdaae2b778e0d7a6d9`

```dockerfile
ENV GOARM=5
```

-	Created: Fri, 08 Jan 2016 14:36:00 GMT
-	Parent Layer: `7fccb073e3909ab6081588fe730ea332b735e73e1319dc51b443f4073f5d6247`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `10b2339a3fa5ad111e0c5d5b7c970571a1248c32cf8625ade29b71741063ec7b`

```dockerfile
RUN cd /usr/src/go/src \
	&& set -ex \
	&& for platform in $GOLANG_CROSSPLATFORMS; do \
		GOOS=${platform%/*} \
		GOARCH=${platform##*/} \
		./make.bash --no-clean 2>&1; \
	done
```

-	Created: Fri, 08 Jan 2016 14:43:32 GMT
-	Parent Layer: `0e1c1441194fd8016f3825487a30ff5b06ba71981635a4bdaae2b778e0d7a6d9`
-	Docker Version: 1.8.3
-	Virtual Size: 1.8 GB (1821789729 bytes)
-	v2 Blob: `sha256:ffef6cd9680faec7d1a1410e53ead5d6cb25f6789608e081125e4d0df97edfe6`
-	v2 Content-Length: 460.5 MB (460537093 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:23:41 GMT

## `golang:1.4-cross`

```console
$ docker pull library/golang@sha256:852c6184da3ff7caf11c61eb11683cc4ac8c9ea080f760023ddea5a9cdfb343a
```

-	Total Virtual Size: 2.4 GB (2384849364 bytes)
-	Total v2 Content-Length: 665.2 MB (665214478 bytes)

### Layers (17)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:34:12 GMT
-	Parent Layer: `10218f130b3e28110bdca1a917b36639887b05d4b4c2893064497cc2bac6cb72`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:34:13 GMT
-	Parent Layer: `37fc5b459ea063941e7cfa251bdfbdb39f7cc59e6e031cdfd5d390d6999ac3f9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:34:51 GMT
-	Parent Layer: `193e7859dee1f88051ce8c8f9d20324c3b43837920586b6190d9cfe9928159ac`
-	Docker Version: 1.8.3
-	Virtual Size: 137.1 MB (137066739 bytes)
-	v2 Blob: `sha256:0c4b77467305f4ce3de876e702258289ca4ba6d760cc630cda8cdf0b53a847a2`
-	v2 Content-Length: 35.4 MB (35417986 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:41 GMT

#### `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:34:53 GMT
-	Parent Layer: `a0b88826c8d1b60e21fc24edb7b06e7796a8f907ce55f39231e5f59d03da011c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:34:54 GMT
-	Parent Layer: `e54b4f25eb658adbee1e3eb1fbd3154366090171672ec26f8de085df46a48ebf`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `f54b8ec65218af41b0deac9621e1b931baeff6d5dc61f6d231bdd621c195f7a9`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f2d95179733c0d3ac19507a4b9e312171b8270459b3b3975879c7464f7cb86b2`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:11 GMT

#### `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:34:56 GMT
-	Parent Layer: `900c406cfa0384e09506545c92186b4670c986f75e1c0980a2be9a848926d1e2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:34:57 GMT
-	Parent Layer: `f9c944a9a09610cd6a7ec2f44c57d2e214e1d71d576f274178c845ed3c85489e`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:ddf5804115182111955f509ae705f549c88d1411bae5c2abeeb5ecca54a712d7`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:14:04 GMT

#### `7fccb073e3909ab6081588fe730ea332b735e73e1319dc51b443f4073f5d6247`

```dockerfile
ENV GOLANG_CROSSPLATFORMS=darwin/386 darwin/amd64 	dragonfly/386 dragonfly/amd64 	freebsd/386 freebsd/amd64 freebsd/arm 	linux/386 linux/amd64 linux/arm 	nacl/386 nacl/amd64p32 nacl/arm 	netbsd/386 netbsd/amd64 netbsd/arm 	openbsd/386 openbsd/amd64 	plan9/386 plan9/amd64 	solaris/amd64 	windows/386 windows/amd64
```

-	Created: Fri, 08 Jan 2016 14:35:59 GMT
-	Parent Layer: `3d92795057123251477049b11c0b0e2fd28735c7252818ac65d5eef1fd304c3e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e1c1441194fd8016f3825487a30ff5b06ba71981635a4bdaae2b778e0d7a6d9`

```dockerfile
ENV GOARM=5
```

-	Created: Fri, 08 Jan 2016 14:36:00 GMT
-	Parent Layer: `7fccb073e3909ab6081588fe730ea332b735e73e1319dc51b443f4073f5d6247`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `10b2339a3fa5ad111e0c5d5b7c970571a1248c32cf8625ade29b71741063ec7b`

```dockerfile
RUN cd /usr/src/go/src \
	&& set -ex \
	&& for platform in $GOLANG_CROSSPLATFORMS; do \
		GOOS=${platform%/*} \
		GOARCH=${platform##*/} \
		./make.bash --no-clean 2>&1; \
	done
```

-	Created: Fri, 08 Jan 2016 14:43:32 GMT
-	Parent Layer: `0e1c1441194fd8016f3825487a30ff5b06ba71981635a4bdaae2b778e0d7a6d9`
-	Docker Version: 1.8.3
-	Virtual Size: 1.8 GB (1821789729 bytes)
-	v2 Blob: `sha256:ffef6cd9680faec7d1a1410e53ead5d6cb25f6789608e081125e4d0df97edfe6`
-	v2 Content-Length: 460.5 MB (460537093 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:23:41 GMT

## `golang:1.4.3-wheezy`

```console
$ docker pull library/golang@sha256:7fec1c5b8565a10d6181b47e0fd036f639f2eb81111394b1b3ebd2cd6d19cafb
```

-	Total Virtual Size: 437.8 MB (437805924 bytes)
-	Total v2 Content-Length: 150.8 MB (150831803 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `0db99107a994bc74425c1fc4cd6b0c907714cd7acd5fcca807345d9ba26a1f83`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:44:19 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `61b4ae64be17b26c3a66a8fedc87cc0cb934a3cf8617cba4bbc21eddf160660f`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:44:20 GMT
-	Parent Layer: `0db99107a994bc74425c1fc4cd6b0c907714cd7acd5fcca807345d9ba26a1f83`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `550da5caab3a98df64890a334b80fd978ddc1fb27ac924d224aa79f7723b4a0b`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:44:20 GMT
-	Parent Layer: `61b4ae64be17b26c3a66a8fedc87cc0cb934a3cf8617cba4bbc21eddf160660f`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `442fb639197cb580de0aa67f809fadfa8270b72ccfdea72535fcfde88ac8752d`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:44:54 GMT
-	Parent Layer: `550da5caab3a98df64890a334b80fd978ddc1fb27ac924d224aa79f7723b4a0b`
-	Docker Version: 1.8.3
-	Virtual Size: 137.9 MB (137895798 bytes)
-	v2 Blob: `sha256:1619f29711f688475795da53f32a20256e958b1b3d6d101697484d3515548b4d`
-	v2 Content-Length: 35.6 MB (35619237 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:29:35 GMT

#### `b1015a97ccd9689cb605b0c2e7d09bbcb8d4a8f4f157370ec2215721c408c9ab`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:44:56 GMT
-	Parent Layer: `442fb639197cb580de0aa67f809fadfa8270b72ccfdea72535fcfde88ac8752d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `628bbddb2594e24a29949f990559c0105b46d8cb770143d59dc28864a5cfc21e`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:44:57 GMT
-	Parent Layer: `b1015a97ccd9689cb605b0c2e7d09bbcb8d4a8f4f157370ec2215721c408c9ab`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1b908c94d49b5f5fdfdaca3663e80218dfbbb6a4265091151768cb126247ec58`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:44:58 GMT
-	Parent Layer: `628bbddb2594e24a29949f990559c0105b46d8cb770143d59dc28864a5cfc21e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:1691f66e83fdfb4eaaee75aa0d2c56b583c915aa57a5875d31b28ba28f4d8785`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:29:04 GMT

#### `36c980fa5ab112fb973f901392413e09df77c0c0a42e8ac2cf3f68d776fb2969`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:44:59 GMT
-	Parent Layer: `1b908c94d49b5f5fdfdaca3663e80218dfbbb6a4265091151768cb126247ec58`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4a7a9ba3cf169fe1e9dd091d37666cdf14929c4111b1b50993284e0b77312189`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:44:59 GMT
-	Parent Layer: `36c980fa5ab112fb973f901392413e09df77c0c0a42e8ac2cf3f68d776fb2969`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:b7a86a39c08062ac612dc2861a427fbf71e9f4fa18af47e51df2d706107f507a`
-	v2 Content-Length: 1.4 KB (1356 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:28:58 GMT

## `golang:1.4-wheezy`

```console
$ docker pull library/golang@sha256:9d0b3ce146bae5f48c7358e3e1fc54a336ef94e453915eeea4748a786dd7abea
```

-	Total Virtual Size: 437.8 MB (437805924 bytes)
-	Total v2 Content-Length: 150.8 MB (150831803 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `0db99107a994bc74425c1fc4cd6b0c907714cd7acd5fcca807345d9ba26a1f83`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Fri, 08 Jan 2016 14:44:19 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `61b4ae64be17b26c3a66a8fedc87cc0cb934a3cf8617cba4bbc21eddf160660f`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Fri, 08 Jan 2016 14:44:20 GMT
-	Parent Layer: `0db99107a994bc74425c1fc4cd6b0c907714cd7acd5fcca807345d9ba26a1f83`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `550da5caab3a98df64890a334b80fd978ddc1fb27ac924d224aa79f7723b4a0b`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Fri, 08 Jan 2016 14:44:20 GMT
-	Parent Layer: `61b4ae64be17b26c3a66a8fedc87cc0cb934a3cf8617cba4bbc21eddf160660f`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `442fb639197cb580de0aa67f809fadfa8270b72ccfdea72535fcfde88ac8752d`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/src -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/src/go/src && ./make.bash --no-clean 2>&1
```

-	Created: Fri, 08 Jan 2016 14:44:54 GMT
-	Parent Layer: `550da5caab3a98df64890a334b80fd978ddc1fb27ac924d224aa79f7723b4a0b`
-	Docker Version: 1.8.3
-	Virtual Size: 137.9 MB (137895798 bytes)
-	v2 Blob: `sha256:1619f29711f688475795da53f32a20256e958b1b3d6d101697484d3515548b4d`
-	v2 Content-Length: 35.6 MB (35619237 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:29:35 GMT

#### `b1015a97ccd9689cb605b0c2e7d09bbcb8d4a8f4f157370ec2215721c408c9ab`

```dockerfile
ENV GOPATH=/go
```

-	Created: Fri, 08 Jan 2016 14:44:56 GMT
-	Parent Layer: `442fb639197cb580de0aa67f809fadfa8270b72ccfdea72535fcfde88ac8752d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `628bbddb2594e24a29949f990559c0105b46d8cb770143d59dc28864a5cfc21e`

```dockerfile
ENV PATH=/go/bin:/usr/src/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Fri, 08 Jan 2016 14:44:57 GMT
-	Parent Layer: `b1015a97ccd9689cb605b0c2e7d09bbcb8d4a8f4f157370ec2215721c408c9ab`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1b908c94d49b5f5fdfdaca3663e80218dfbbb6a4265091151768cb126247ec58`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Fri, 08 Jan 2016 14:44:58 GMT
-	Parent Layer: `628bbddb2594e24a29949f990559c0105b46d8cb770143d59dc28864a5cfc21e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:1691f66e83fdfb4eaaee75aa0d2c56b583c915aa57a5875d31b28ba28f4d8785`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Mon, 11 Jan 2016 18:29:04 GMT

#### `36c980fa5ab112fb973f901392413e09df77c0c0a42e8ac2cf3f68d776fb2969`

```dockerfile
WORKDIR /go
```

-	Created: Fri, 08 Jan 2016 14:44:59 GMT
-	Parent Layer: `1b908c94d49b5f5fdfdaca3663e80218dfbbb6a4265091151768cb126247ec58`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4a7a9ba3cf169fe1e9dd091d37666cdf14929c4111b1b50993284e0b77312189`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Fri, 08 Jan 2016 14:44:59 GMT
-	Parent Layer: `36c980fa5ab112fb973f901392413e09df77c0c0a42e8ac2cf3f68d776fb2969`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:b7a86a39c08062ac612dc2861a427fbf71e9f4fa18af47e51df2d706107f507a`
-	v2 Content-Length: 1.4 KB (1356 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:28:58 GMT

## `golang:1.4.3-alpine`

```console
$ docker pull library/golang@sha256:c14730d32a5a30e3013fb05cd67db470e8422e353c45e3b711adda71bbbf899f
```

-	Total Virtual Size: 143.1 MB (143063007 bytes)
-	Total v2 Content-Length: 38.1 MB (38113797 bytes)

### Layers (9)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `e40fb7c623e205eab51421f701050d56f4b901328316e28e465addf0d63b3ae4`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Mon, 04 Jan 2016 19:22:07 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `174f97d1f31a46190086fc7e8f44bd98a45824d40afe707540e97acfc8342a54`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Mon, 04 Jan 2016 19:22:08 GMT
-	Parent Layer: `e40fb7c623e205eab51421f701050d56f4b901328316e28e465addf0d63b3ae4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b3d016ac8ddb4f30f69aaada0aca70ac528d6aaa5ae40234688c6b7ac8d7308b`

```dockerfile
ENV GOLANG_SRC_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Mon, 04 Jan 2016 19:22:09 GMT
-	Parent Layer: `174f97d1f31a46190086fc7e8f44bd98a45824d40afe707540e97acfc8342a54`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `16d853ac1a192e9f2670023cad213361e380179d421923ec1d0b04bc3cd92e1a`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& apk del .build-deps
```

-	Created: Mon, 04 Jan 2016 19:23:11 GMT
-	Parent Layer: `b3d016ac8ddb4f30f69aaada0aca70ac528d6aaa5ae40234688c6b7ac8d7308b`
-	Docker Version: 1.8.3
-	Virtual Size: 138.3 MB (138269068 bytes)
-	v2 Blob: `sha256:4ce127434adf5406a59c471bfa0c68e6668a592dce3d822c7608332b7f820505`
-	v2 Content-Length: 35.8 MB (35794554 bytes)
-	v2 Last-Modified: Mon, 04 Jan 2016 20:11:58 GMT

#### `0b997d06d27402594a562bc0887749b4c1b58d45ee43eda4b69c0f88c8162a6c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Mon, 04 Jan 2016 19:23:22 GMT
-	Parent Layer: `16d853ac1a192e9f2670023cad213361e380179d421923ec1d0b04bc3cd92e1a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `68e1984d74574a8d44d29de844794c5772a0a6ddda7a6da1dbd476ba16a321f2`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Mon, 04 Jan 2016 19:23:23 GMT
-	Parent Layer: `0b997d06d27402594a562bc0887749b4c1b58d45ee43eda4b69c0f88c8162a6c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `17e3f873943581ceba86dbdf9350ca52cd08c2b7920d325abd11a4106a2c7f39`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Mon, 04 Jan 2016 19:23:25 GMT
-	Parent Layer: `68e1984d74574a8d44d29de844794c5772a0a6ddda7a6da1dbd476ba16a321f2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:60c04686f42795d31197cf9a35b44c8073864291170eae9dd22af736f4934947`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 04 Jan 2016 20:11:27 GMT

#### `e5515028a8aae7cf1ed9a6f9342aef2b933941e27003ab872fc883321a2a5799`

```dockerfile
WORKDIR /go
```

-	Created: Mon, 04 Jan 2016 19:23:26 GMT
-	Parent Layer: `17e3f873943581ceba86dbdf9350ca52cd08c2b7920d325abd11a4106a2c7f39`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.4-alpine`

```console
$ docker pull library/golang@sha256:2e0ca68bb827f4683fec4191da3f011cba4325891b5aa14b7a91919fab1e3b33
```

-	Total Virtual Size: 143.1 MB (143063007 bytes)
-	Total v2 Content-Length: 38.1 MB (38113797 bytes)

### Layers (9)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `e40fb7c623e205eab51421f701050d56f4b901328316e28e465addf0d63b3ae4`

```dockerfile
ENV GOLANG_VERSION=1.4.3
```

-	Created: Mon, 04 Jan 2016 19:22:07 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `174f97d1f31a46190086fc7e8f44bd98a45824d40afe707540e97acfc8342a54`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Mon, 04 Jan 2016 19:22:08 GMT
-	Parent Layer: `e40fb7c623e205eab51421f701050d56f4b901328316e28e465addf0d63b3ae4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b3d016ac8ddb4f30f69aaada0aca70ac528d6aaa5ae40234688c6b7ac8d7308b`

```dockerfile
ENV GOLANG_SRC_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Mon, 04 Jan 2016 19:22:09 GMT
-	Parent Layer: `174f97d1f31a46190086fc7e8f44bd98a45824d40afe707540e97acfc8342a54`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `16d853ac1a192e9f2670023cad213361e380179d421923ec1d0b04bc3cd92e1a`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& apk del .build-deps
```

-	Created: Mon, 04 Jan 2016 19:23:11 GMT
-	Parent Layer: `b3d016ac8ddb4f30f69aaada0aca70ac528d6aaa5ae40234688c6b7ac8d7308b`
-	Docker Version: 1.8.3
-	Virtual Size: 138.3 MB (138269068 bytes)
-	v2 Blob: `sha256:4ce127434adf5406a59c471bfa0c68e6668a592dce3d822c7608332b7f820505`
-	v2 Content-Length: 35.8 MB (35794554 bytes)
-	v2 Last-Modified: Mon, 04 Jan 2016 20:11:58 GMT

#### `0b997d06d27402594a562bc0887749b4c1b58d45ee43eda4b69c0f88c8162a6c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Mon, 04 Jan 2016 19:23:22 GMT
-	Parent Layer: `16d853ac1a192e9f2670023cad213361e380179d421923ec1d0b04bc3cd92e1a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `68e1984d74574a8d44d29de844794c5772a0a6ddda7a6da1dbd476ba16a321f2`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Mon, 04 Jan 2016 19:23:23 GMT
-	Parent Layer: `0b997d06d27402594a562bc0887749b4c1b58d45ee43eda4b69c0f88c8162a6c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `17e3f873943581ceba86dbdf9350ca52cd08c2b7920d325abd11a4106a2c7f39`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Mon, 04 Jan 2016 19:23:25 GMT
-	Parent Layer: `68e1984d74574a8d44d29de844794c5772a0a6ddda7a6da1dbd476ba16a321f2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:60c04686f42795d31197cf9a35b44c8073864291170eae9dd22af736f4934947`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Mon, 04 Jan 2016 20:11:27 GMT

#### `e5515028a8aae7cf1ed9a6f9342aef2b933941e27003ab872fc883321a2a5799`

```dockerfile
WORKDIR /go
```

-	Created: Mon, 04 Jan 2016 19:23:26 GMT
-	Parent Layer: `17e3f873943581ceba86dbdf9350ca52cd08c2b7920d325abd11a4106a2c7f39`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.5.3`

```console
$ docker pull library/golang@sha256:fb76c4067bad62083eb602875c82cd095cc4f3596d59f643b0a7d90e2d3272e5
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408203 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

## `golang:1.5`

```console
$ docker pull library/golang@sha256:f760e3b5985950655845b0c2c6e8e537ba4adb6440eab89d230b84464905cedc
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408203 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

## `golang:1`

```console
$ docker pull library/golang@sha256:c89072437ebf132734f04ffda953a7ba5b1be5c20dfd12942f0b340eef4f8c41
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408203 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

## `golang:latest`

```console
$ docker pull library/golang@sha256:8b699479ec2676f675343039a58b4be192aadcb446871465c4dd91985e8e1076
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408203 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

## `golang:1.5.3-onbuild`

```console
$ docker pull library/golang@sha256:476f4e9d118700bfbc819638bedd16235b757638aaf2716a778ce15949a6be7e
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408495 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

#### `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:d0ca873ae3ffeeb1c46744e39510da9f24ad5e8bef2f9ca90a35a18ef10fc4a5`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:53:38 GMT

#### `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Wed, 13 Jan 2016 22:27:18 GMT
-	Parent Layer: `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `546093df6cdb503a85da9a5282c33b588b5b4cd6595102a36fab5c6d5da29e00`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Wed, 13 Jan 2016 22:27:20 GMT
-	Parent Layer: `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.5-onbuild`

```console
$ docker pull library/golang@sha256:11ff9b50cf4a7e00497812c226f5ee8497b47a59fe6e858130a16d1e72fe5801
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408495 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

#### `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:d0ca873ae3ffeeb1c46744e39510da9f24ad5e8bef2f9ca90a35a18ef10fc4a5`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:53:38 GMT

#### `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Wed, 13 Jan 2016 22:27:18 GMT
-	Parent Layer: `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `546093df6cdb503a85da9a5282c33b588b5b4cd6595102a36fab5c6d5da29e00`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Wed, 13 Jan 2016 22:27:20 GMT
-	Parent Layer: `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1-onbuild`

```console
$ docker pull library/golang@sha256:d77e941663d0299f3c3eea311a448d36f5397a6c873250e5a76bc409889d7e34
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408495 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

#### `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:d0ca873ae3ffeeb1c46744e39510da9f24ad5e8bef2f9ca90a35a18ef10fc4a5`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:53:38 GMT

#### `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Wed, 13 Jan 2016 22:27:18 GMT
-	Parent Layer: `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `546093df6cdb503a85da9a5282c33b588b5b4cd6595102a36fab5c6d5da29e00`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Wed, 13 Jan 2016 22:27:20 GMT
-	Parent Layer: `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:onbuild`

```console
$ docker pull library/golang@sha256:a8038c48c10d285ad71e5a937d2402766a78b9710467895d44bacfbf62374aa2
```

-	Total Virtual Size: 725.1 MB (725134268 bytes)
-	Total v2 Content-Length: 249.4 MB (249408495 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:26 GMT
-	Parent Layer: `f9ef0f46580d66a8aa4546741a973c7bbea01d3d48fa6cf2fc1af25b7dc73886`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:25:27 GMT
-	Parent Layer: `f055aaf2cebd355abd55f9059e537d6975797291697bfadab5ef7253b819fd03`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:25:33 GMT
-	Parent Layer: `4662c59550d2acdfb26f37f2c88af2328901c8566df23f82b67e11a4ea0971fd`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:e98ec1596fcd89b7b3907ba8e05ac264613f70a95ec3c6da4e17d1c612d7303a`
-	v2 Content-Length: 80.1 MB (80148867 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:51:25 GMT

#### `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:25:36 GMT
-	Parent Layer: `206a26ed4401dbb01e74e41dcff4aa88dfecea7e26df53e65fb31c5e1a9f4448`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:25:37 GMT
-	Parent Layer: `da329b744c90f2c87db75b00781c0edecf2439d64e98160332671c664d860d79`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:25:38 GMT
-	Parent Layer: `eb4ecdf2774c9a384c3c5cce69b640844c7e7d0ee875f62a6ab8e899ab372469`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:5043f97a6e070b9ba51f2e3c2a453acbfc3023fa01ea91f61d933590626fd7b5`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:37 GMT

#### `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:25:39 GMT
-	Parent Layer: `fbe1fe6511535c3ee5c68520220bc1aab9954c08d0291744f37b1f40bfcaae53`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:25:40 GMT
-	Parent Layer: `b36c0904b4a4f0e8b19a5dd2a1bb19c479dcd28c7d4504c223606f8c8acf3545`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:7d86f173eee430ff65d672dee691ea8ffddfae2b6eabdb19fd4e58bc20f68a46`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:50:30 GMT

#### `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `59f2b86b56a6e929f009571a677248babce3eee8cf466fd64e3d372449a23a6b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:d0ca873ae3ffeeb1c46744e39510da9f24ad5e8bef2f9ca90a35a18ef10fc4a5`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:53:38 GMT

#### `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:17 GMT
-	Parent Layer: `783f45ec42560ff5dfb1dea2383e10232187310ec6f9dbaef575598c02feae84`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Wed, 13 Jan 2016 22:27:18 GMT
-	Parent Layer: `bc0fbc59819006fc991e394a4e3d1ddbb6a5620cd5a4b8751fe4edcac32bb9d3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `843463fec533d1bba08378db2a420a8dd5bca9a112fef839c657ec74cb5122b3`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Wed, 13 Jan 2016 22:27:19 GMT
-	Parent Layer: `add6029c21ede81f618413ba286ff5956afeb2d8ac17629280834ee46e284155`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `546093df6cdb503a85da9a5282c33b588b5b4cd6595102a36fab5c6d5da29e00`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Wed, 13 Jan 2016 22:27:20 GMT
-	Parent Layer: `99de2996d72815795e6688756e36a32fc664f6487fa8fe29a3193de0050a10c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.5.3-wheezy`

```console
$ docker pull library/golang@sha256:0d46c54e064902bde2b285179ea0472ecb40a7980fd718f73cfcd552bd0a2341
```

-	Total Virtual Size: 599.1 MB (599051498 bytes)
-	Total v2 Content-Length: 195.4 MB (195361424 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:28:24 GMT
-	Parent Layer: `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:30 GMT
-	Parent Layer: `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:cdcbad8a103746daf2737609a3b9bcb3298c43a04240a23c6edb41aa1ea9ff29`
-	v2 Content-Length: 80.1 MB (80148865 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:55:47 GMT

#### `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:28:33 GMT
-	Parent Layer: `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:28:34 GMT
-	Parent Layer: `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b134052773a51bb1d808d9b4aa5e2f5cfcdb071f11a9768d85e14f0902e8c67f`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:59 GMT

#### `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d6a4ddbaf4cee63117548ebb2d12be18695dbf013db56516463075e5af72e483`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:28:37 GMT
-	Parent Layer: `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:1078815df07542a1a5c0160061bf21167c3aa7693b9353db77ab6a515722f494`
-	v2 Content-Length: 1.4 KB (1350 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:53 GMT

## `golang:1.5-wheezy`

```console
$ docker pull library/golang@sha256:77f42c51227a182556a6fb2c9a74445eaf75972bb5677fa834c0fdc81f2314b9
```

-	Total Virtual Size: 599.1 MB (599051498 bytes)
-	Total v2 Content-Length: 195.4 MB (195361424 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:28:24 GMT
-	Parent Layer: `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:30 GMT
-	Parent Layer: `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:cdcbad8a103746daf2737609a3b9bcb3298c43a04240a23c6edb41aa1ea9ff29`
-	v2 Content-Length: 80.1 MB (80148865 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:55:47 GMT

#### `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:28:33 GMT
-	Parent Layer: `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:28:34 GMT
-	Parent Layer: `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b134052773a51bb1d808d9b4aa5e2f5cfcdb071f11a9768d85e14f0902e8c67f`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:59 GMT

#### `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d6a4ddbaf4cee63117548ebb2d12be18695dbf013db56516463075e5af72e483`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:28:37 GMT
-	Parent Layer: `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:1078815df07542a1a5c0160061bf21167c3aa7693b9353db77ab6a515722f494`
-	v2 Content-Length: 1.4 KB (1350 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:53 GMT

## `golang:1-wheezy`

```console
$ docker pull library/golang@sha256:abf73db7056dc3bf6118d3853e8e4f3497dc00f5f763806d6c0fe7826869966e
```

-	Total Virtual Size: 599.1 MB (599051498 bytes)
-	Total v2 Content-Length: 195.4 MB (195361424 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:28:24 GMT
-	Parent Layer: `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:30 GMT
-	Parent Layer: `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:cdcbad8a103746daf2737609a3b9bcb3298c43a04240a23c6edb41aa1ea9ff29`
-	v2 Content-Length: 80.1 MB (80148865 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:55:47 GMT

#### `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:28:33 GMT
-	Parent Layer: `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:28:34 GMT
-	Parent Layer: `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b134052773a51bb1d808d9b4aa5e2f5cfcdb071f11a9768d85e14f0902e8c67f`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:59 GMT

#### `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d6a4ddbaf4cee63117548ebb2d12be18695dbf013db56516463075e5af72e483`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:28:37 GMT
-	Parent Layer: `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:1078815df07542a1a5c0160061bf21167c3aa7693b9353db77ab6a515722f494`
-	v2 Content-Length: 1.4 KB (1350 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:53 GMT

## `golang:wheezy`

```console
$ docker pull library/golang@sha256:7ea07ecef905b9a3271a688aeaa09ffe9d0767c4690c415f8a0e664f85e3a8d4
```

-	Total Virtual Size: 599.1 MB (599051498 bytes)
-	Total v2 Content-Length: 195.4 MB (195361424 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.3.linux-amd64.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:23 GMT
-	Parent Layer: `4ad45a0e4591a412a8c33f055898462c47b776848e1590d2be512a5b1f95b09e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=43afe0c5017e502630b1aea4d44b8a7f059bf60d7f29dfd58db454d4e4e0ae53
```

-	Created: Wed, 13 Jan 2016 22:28:24 GMT
-	Parent Layer: `14ec64010f9a2d7ad435f8ab2a970d888aa3a3e6ef5451404c6d2c938e8c0292`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:28:30 GMT
-	Parent Layer: `cdb4f90520adf6d4f007425e38d268dd6ec2c3d4037726c5676e13c75a68f845`
-	Docker Version: 1.8.3
-	Virtual Size: 299.1 MB (299141372 bytes)
-	v2 Blob: `sha256:cdcbad8a103746daf2737609a3b9bcb3298c43a04240a23c6edb41aa1ea9ff29`
-	v2 Content-Length: 80.1 MB (80148865 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:55:47 GMT

#### `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:28:33 GMT
-	Parent Layer: `0ba941fe34ccc00acd8dc5887a10746ed5659453650721200f302f549296354b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:28:34 GMT
-	Parent Layer: `3a5029984b4d6b2c649383cf17459d8d1e04c40851d31c581d867ed109ec393c`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `4defaacbd13d4d59f230f31e1a7efa6983bfafb5b4b7f209c8feead97a7cc24d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b134052773a51bb1d808d9b4aa5e2f5cfcdb071f11a9768d85e14f0902e8c67f`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:59 GMT

#### `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:28:36 GMT
-	Parent Layer: `ae789a7510d55756541287d97fed47ede7cd72f0c1f8b01693d16add536024ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d6a4ddbaf4cee63117548ebb2d12be18695dbf013db56516463075e5af72e483`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Wed, 13 Jan 2016 22:28:37 GMT
-	Parent Layer: `68ae9b9b69b496f1018d45007c106843c59adb977f164caa8a05c36f47949d8d`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:1078815df07542a1a5c0160061bf21167c3aa7693b9353db77ab6a515722f494`
-	v2 Content-Length: 1.4 KB (1350 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:54:53 GMT

## `golang:1.5.3-alpine`

```console
$ docker pull library/golang@sha256:46e08296e6d308eca68aa7b2bbaab9d4d971d2a1196c36656e4e9496ad2eca2e
```

-	Total Virtual Size: 262.1 MB (262050438 bytes)
-	Total v2 Content-Length: 66.8 MB (66815524 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`

```dockerfile
ENV GOLANG_SRC_SHA256=754e06dab1c31ab168fc9db9e32596734015ea9e24bc44cae7f237f417ce4efe
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:15 GMT
-	Parent Layer: `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Wed, 13 Jan 2016 22:30:16 GMT
-	Parent Layer: `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Wed, 13 Jan 2016 22:32:05 GMT
-	Parent Layer: `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`
-	Docker Version: 1.8.3
-	Virtual Size: 257.3 MB (257256499 bytes)
-	v2 Blob: `sha256:4988cc535db2dcf6eebec82e6a501050509d829069ff390e078925880d412c98`
-	v2 Content-Length: 64.5 MB (64496184 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:58:29 GMT

#### `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:32:08 GMT
-	Parent Layer: `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:32:09 GMT
-	Parent Layer: `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b75cf27b4387b67a6a47b1a1bfcf1fbf78dcadeb1b095f1cd375d6ff705f88e6`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:57:46 GMT

#### `6a945e77a678b0ac51840c7995006bf1e0286917be8f295e16936fff70df2b45`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.5-alpine`

```console
$ docker pull library/golang@sha256:7cdfa2e077e8514f638a1b95f213209f8cd6c6b499caf851b2f6b986c15d7fb3
```

-	Total Virtual Size: 262.1 MB (262050438 bytes)
-	Total v2 Content-Length: 66.8 MB (66815524 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`

```dockerfile
ENV GOLANG_SRC_SHA256=754e06dab1c31ab168fc9db9e32596734015ea9e24bc44cae7f237f417ce4efe
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:15 GMT
-	Parent Layer: `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Wed, 13 Jan 2016 22:30:16 GMT
-	Parent Layer: `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Wed, 13 Jan 2016 22:32:05 GMT
-	Parent Layer: `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`
-	Docker Version: 1.8.3
-	Virtual Size: 257.3 MB (257256499 bytes)
-	v2 Blob: `sha256:4988cc535db2dcf6eebec82e6a501050509d829069ff390e078925880d412c98`
-	v2 Content-Length: 64.5 MB (64496184 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:58:29 GMT

#### `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:32:08 GMT
-	Parent Layer: `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:32:09 GMT
-	Parent Layer: `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b75cf27b4387b67a6a47b1a1bfcf1fbf78dcadeb1b095f1cd375d6ff705f88e6`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:57:46 GMT

#### `6a945e77a678b0ac51840c7995006bf1e0286917be8f295e16936fff70df2b45`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1-alpine`

```console
$ docker pull library/golang@sha256:c62c666bff7e7e2234a1505e4e7badc14aba7113c9e4f36cc49d72709a348347
```

-	Total Virtual Size: 262.1 MB (262050438 bytes)
-	Total v2 Content-Length: 66.8 MB (66815524 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`

```dockerfile
ENV GOLANG_SRC_SHA256=754e06dab1c31ab168fc9db9e32596734015ea9e24bc44cae7f237f417ce4efe
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:15 GMT
-	Parent Layer: `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Wed, 13 Jan 2016 22:30:16 GMT
-	Parent Layer: `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Wed, 13 Jan 2016 22:32:05 GMT
-	Parent Layer: `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`
-	Docker Version: 1.8.3
-	Virtual Size: 257.3 MB (257256499 bytes)
-	v2 Blob: `sha256:4988cc535db2dcf6eebec82e6a501050509d829069ff390e078925880d412c98`
-	v2 Content-Length: 64.5 MB (64496184 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:58:29 GMT

#### `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:32:08 GMT
-	Parent Layer: `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:32:09 GMT
-	Parent Layer: `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b75cf27b4387b67a6a47b1a1bfcf1fbf78dcadeb1b095f1cd375d6ff705f88e6`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:57:46 GMT

#### `6a945e77a678b0ac51840c7995006bf1e0286917be8f295e16936fff70df2b45`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:alpine`

```console
$ docker pull library/golang@sha256:4da6ceaf2152b9fa51caad80e10a2ceeefbd1553602e2e15b5c4e59148e9ab48
```

-	Total Virtual Size: 262.1 MB (262050438 bytes)
-	Total v2 Content-Length: 66.8 MB (66815524 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`

```dockerfile
ENV GOLANG_VERSION=1.5.3
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:13 GMT
-	Parent Layer: `74065d86543365f51f4637376297214d284cc1cac995662dd325dc5c4f5f5a0a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`

```dockerfile
ENV GOLANG_SRC_SHA256=754e06dab1c31ab168fc9db9e32596734015ea9e24bc44cae7f237f417ce4efe
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `ed9169ffe88a20fd173090888c8926905756cafbd9843074971f720b8421fa4a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Wed, 13 Jan 2016 22:30:14 GMT
-	Parent Layer: `dcb1fbf8f9756d3376f5e1bacfd324e587db8fdbf38fc89881df746a5523fdf8`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Wed, 13 Jan 2016 22:30:15 GMT
-	Parent Layer: `78c59829f78f51fa53bc1f6805bed3a92ca478a1ed401e52275d7ec1605f4af4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Wed, 13 Jan 2016 22:30:16 GMT
-	Parent Layer: `3f36eea1c48db3780c69b66a8ae586883f3b1c9eab5ada72f7e662444bf2c8e1`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Wed, 13 Jan 2016 22:32:05 GMT
-	Parent Layer: `7a084bc6e2b916dfc9b3c24d5914d0ffa1065a2010e6fa1657c27b5ae780d4dd`
-	Docker Version: 1.8.3
-	Virtual Size: 257.3 MB (257256499 bytes)
-	v2 Blob: `sha256:4988cc535db2dcf6eebec82e6a501050509d829069ff390e078925880d412c98`
-	v2 Content-Length: 64.5 MB (64496184 bytes)
-	v2 Last-Modified: Wed, 13 Jan 2016 22:58:29 GMT

#### `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`

```dockerfile
ENV GOPATH=/go
```

-	Created: Wed, 13 Jan 2016 22:32:08 GMT
-	Parent Layer: `b2b4fa17bd5f9a5e88cb49d9a75d2fa9477a44cdd40982a1dcd95cb541b69e64`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Wed, 13 Jan 2016 22:32:09 GMT
-	Parent Layer: `f9288a9add54f3e83602a076a03475965e86faf7838a51233894fd967626e164`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `5f3a45fdb289c8c0519b877713c43b945cf3733836df646c9feed55a7d25aedc`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b75cf27b4387b67a6a47b1a1bfcf1fbf78dcadeb1b095f1cd375d6ff705f88e6`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Wed, 13 Jan 2016 22:57:46 GMT

#### `6a945e77a678b0ac51840c7995006bf1e0286917be8f295e16936fff70df2b45`

```dockerfile
WORKDIR /go
```

-	Created: Wed, 13 Jan 2016 22:32:11 GMT
-	Parent Layer: `00483c40ebab0e63b8bdd94dc2ccb4a74c0ec994a5aa4c9ec966a2e5baad6c74`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.6beta2`

```console
$ docker pull library/golang@sha256:6daff6641ebb81e2e3a6dfbcb18e584c0f230a33127c84d7a946738fc52c8f71
```

-	Total Virtual Size: 747.0 MB (746972288 bytes)
-	Total v2 Content-Length: 255.1 MB (255119952 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:15:52 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:15:53 GMT
-	Parent Layer: `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:15:54 GMT
-	Parent Layer: `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:16:00 GMT
-	Parent Layer: `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:0b9e526a12b943c2353a9e751b6114770d8650b43e8ae41d9e117c541a6f79f7`
-	v2 Content-Length: 85.9 MB (85860619 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:30:20 GMT

#### `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:16:03 GMT
-	Parent Layer: `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:16:04 GMT
-	Parent Layer: `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a2abeeaf5fc0b46bb99ccac5abcd78cfc7cc1e6651c2f77fd491b8b79e142389`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:30 GMT

#### `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:16:07 GMT
-	Parent Layer: `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:051e9819f63ae3e3d448ee25b819f750984d067d035340bf3712b6c7c13c98e3`
-	v2 Content-Length: 1.4 KB (1352 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:24 GMT

## `golang:1.6`

```console
$ docker pull library/golang@sha256:09b21218ed07b5b79e345e6c6955096e4583e1d434c8898efd99f35d9b11312f
```

-	Total Virtual Size: 747.0 MB (746972288 bytes)
-	Total v2 Content-Length: 255.1 MB (255119952 bytes)

### Layers (14)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:15:52 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:15:53 GMT
-	Parent Layer: `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:15:54 GMT
-	Parent Layer: `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:16:00 GMT
-	Parent Layer: `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:0b9e526a12b943c2353a9e751b6114770d8650b43e8ae41d9e117c541a6f79f7`
-	v2 Content-Length: 85.9 MB (85860619 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:30:20 GMT

#### `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:16:03 GMT
-	Parent Layer: `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:16:04 GMT
-	Parent Layer: `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a2abeeaf5fc0b46bb99ccac5abcd78cfc7cc1e6651c2f77fd491b8b79e142389`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:30 GMT

#### `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:16:07 GMT
-	Parent Layer: `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:051e9819f63ae3e3d448ee25b819f750984d067d035340bf3712b6c7c13c98e3`
-	v2 Content-Length: 1.4 KB (1352 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:24 GMT

## `golang:1.6beta2-onbuild`

```console
$ docker pull library/golang@sha256:de8e9de947b68604959332d1a2682603afafa318e5276bfc8bad957b08cadfc1
```

-	Total Virtual Size: 747.0 MB (746972288 bytes)
-	Total v2 Content-Length: 255.1 MB (255120244 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:15:52 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:15:53 GMT
-	Parent Layer: `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:15:54 GMT
-	Parent Layer: `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:16:00 GMT
-	Parent Layer: `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:0b9e526a12b943c2353a9e751b6114770d8650b43e8ae41d9e117c541a6f79f7`
-	v2 Content-Length: 85.9 MB (85860619 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:30:20 GMT

#### `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:16:03 GMT
-	Parent Layer: `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:16:04 GMT
-	Parent Layer: `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a2abeeaf5fc0b46bb99ccac5abcd78cfc7cc1e6651c2f77fd491b8b79e142389`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:30 GMT

#### `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:16:07 GMT
-	Parent Layer: `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:051e9819f63ae3e3d448ee25b819f750984d067d035340bf3712b6c7c13c98e3`
-	v2 Content-Length: 1.4 KB (1352 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:24 GMT

#### `6fbe80ba915bf41edd2cd7aaa0aa8827d452d72a5cc2b214bfce0912619f9b9b`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:43 GMT
-	Parent Layer: `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:8e6ed43457730403cf4fa6f1956b2dd7328a50895ea2fd38e52871faeff1f4a0`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:32:46 GMT

#### `62e9a9e73709d84127aa95cb506d875e527485ffd0c04beadae658981755c9a0`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:44 GMT
-	Parent Layer: `6fbe80ba915bf41edd2cd7aaa0aa8827d452d72a5cc2b214bfce0912619f9b9b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `708e61d56f98678721e05f397ad861c5bb1ed7260d9bb4002b67fec7d9d246a0`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Thu, 14 Jan 2016 17:16:44 GMT
-	Parent Layer: `62e9a9e73709d84127aa95cb506d875e527485ffd0c04beadae658981755c9a0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81d6ef50b37e51d57a91c06a4e7ab1c5e73d447c6ab0c6ae8e8f3b9fa3ad392e`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:45 GMT
-	Parent Layer: `708e61d56f98678721e05f397ad861c5bb1ed7260d9bb4002b67fec7d9d246a0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bfbba38b8b997035e4eafb082c12da5707dddb2b66c5ca44f0b7ce7db103464e`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Thu, 14 Jan 2016 17:16:45 GMT
-	Parent Layer: `81d6ef50b37e51d57a91c06a4e7ab1c5e73d447c6ab0c6ae8e8f3b9fa3ad392e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `724b07a26619a29f8bb2c0f04bcf488a515c86b223d4cbb12edecf39202a5a53`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Thu, 14 Jan 2016 17:16:46 GMT
-	Parent Layer: `bfbba38b8b997035e4eafb082c12da5707dddb2b66c5ca44f0b7ce7db103464e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.6-onbuild`

```console
$ docker pull library/golang@sha256:301add306242fd2f87a6c45695db713dac681735928e2fcc8850ee62360d89bd
```

-	Total Virtual Size: 747.0 MB (746972288 bytes)
-	Total v2 Content-Length: 255.1 MB (255120244 bytes)

### Layers (20)

#### `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`

```dockerfile
ADD file:0098703cdfd5b5eda3aececc4d4600b0fb4b753e19c832c73df4f9d5fdcf3598 in /
```

-	Created: Thu, 07 Jan 2016 01:07:09 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:81cc5f26a6a083c024fb4138326e4d00f9a73f60c0e2a4399e1f7617ebe8c6c9`
-	v2 Content-Length: 51.4 MB (51354018 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:51 GMT

#### `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:07:11 GMT
-	Parent Layer: `cb6fb082434ea9d7f25798e96abc06cb176cbe910970ec86874555e7c9fbc04a`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:23:12 GMT
-	Parent Layer: `d4b2ba78e3b4b44bdfab5b625c210d6e410debba50446520fe1c3e1a5ee9cdea`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:5a4693d81fc51b1594bf4437320c840a794a421a6bb71bb006d28a7394060722`
-	v2 Content-Length: 18.5 MB (18528699 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:34:13 GMT

#### `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:24:12 GMT
-	Parent Layer: `706c9f1cbd8cd495ede6616faa1010202e8941e237666b2095b70a89c554c67e`
-	Docker Version: 1.8.3
-	Virtual Size: 122.6 MB (122576462 bytes)
-	v2 Blob: `sha256:9c2c7d262d052b10af9cfc948ce3811d0f873b3d79d34da45dc1f45455f54ccc`
-	v2 Content-Length: 42.5 MB (42492912 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:36:15 GMT

#### `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:34:10 GMT
-	Parent Layer: `215e4fe64afcf03bb0a2a9956c68fe017262acf98ae348715325c93abd44d933`
-	Docker Version: 1.8.3
-	Virtual Size: 134.0 MB (134005183 bytes)
-	v2 Blob: `sha256:b4b74c6f233974d157f47c176fa4cd3d6ea2b066792887ac5c6fc1969d5f9777`
-	v2 Content-Length: 56.9 MB (56882005 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:15:20 GMT

#### `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:15:52 GMT
-	Parent Layer: `251f1f3f88aa93da40bacd191f0aa986e53eaa53be5c18e17c10b13173cfcd00`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:15:53 GMT
-	Parent Layer: `48c4db8a5fd67275885a4a20c0260a39ff64f65ee3e52c386e41576f22382b32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:15:54 GMT
-	Parent Layer: `e785c396c1e382debc2b99a3eb556e7c5c715e16acb069f30484ac1d022d35ff`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:16:00 GMT
-	Parent Layer: `f7f1d7b01d36d710cca64e299a9419383d6be69191513d198eb175ffac434f2d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:0b9e526a12b943c2353a9e751b6114770d8650b43e8ae41d9e117c541a6f79f7`
-	v2 Content-Length: 85.9 MB (85860619 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:30:20 GMT

#### `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:16:03 GMT
-	Parent Layer: `0f85a3f49479c4c3bb7a291c839b05f9f242bbd8d4f17ea307f7d888ccadf6cd`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:16:04 GMT
-	Parent Layer: `535f07633a6154b1646024aa5ab2744f5b8f023de73cf6065bb1b21752d01ed2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `2aa28fef95ef1d9ac6010dce997315aacc5f886c82f575f3f1249c1619320e32`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a2abeeaf5fc0b46bb99ccac5abcd78cfc7cc1e6651c2f77fd491b8b79e142389`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:30 GMT

#### `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:16:06 GMT
-	Parent Layer: `f8d2c670673949aba9c802b23cf4f185b1fee5bd7569ee6788083c3614e337f7`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:16:07 GMT
-	Parent Layer: `178e440bbf848530be34329c41b12b76c8691e4eef34d2d858a7e5449b1cc3bd`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:051e9819f63ae3e3d448ee25b819f750984d067d035340bf3712b6c7c13c98e3`
-	v2 Content-Length: 1.4 KB (1352 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:29:24 GMT

#### `6fbe80ba915bf41edd2cd7aaa0aa8827d452d72a5cc2b214bfce0912619f9b9b`

```dockerfile
RUN mkdir -p /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:43 GMT
-	Parent Layer: `e186e73b52b55747d9558bb71c930b3a0067a664be04a2a3844932de7626af87`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:8e6ed43457730403cf4fa6f1956b2dd7328a50895ea2fd38e52871faeff1f4a0`
-	v2 Content-Length: 132.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:32:46 GMT

#### `62e9a9e73709d84127aa95cb506d875e527485ffd0c04beadae658981755c9a0`

```dockerfile
WORKDIR /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:44 GMT
-	Parent Layer: `6fbe80ba915bf41edd2cd7aaa0aa8827d452d72a5cc2b214bfce0912619f9b9b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `708e61d56f98678721e05f397ad861c5bb1ed7260d9bb4002b67fec7d9d246a0`

```dockerfile
CMD ["go-wrapper" "run"]
```

-	Created: Thu, 14 Jan 2016 17:16:44 GMT
-	Parent Layer: `62e9a9e73709d84127aa95cb506d875e527485ffd0c04beadae658981755c9a0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81d6ef50b37e51d57a91c06a4e7ab1c5e73d447c6ab0c6ae8e8f3b9fa3ad392e`

```dockerfile
ONBUILD COPY . /go/src/app
```

-	Created: Thu, 14 Jan 2016 17:16:45 GMT
-	Parent Layer: `708e61d56f98678721e05f397ad861c5bb1ed7260d9bb4002b67fec7d9d246a0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bfbba38b8b997035e4eafb082c12da5707dddb2b66c5ca44f0b7ce7db103464e`

```dockerfile
ONBUILD RUN go-wrapper download
```

-	Created: Thu, 14 Jan 2016 17:16:45 GMT
-	Parent Layer: `81d6ef50b37e51d57a91c06a4e7ab1c5e73d447c6ab0c6ae8e8f3b9fa3ad392e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `724b07a26619a29f8bb2c0f04bcf488a515c86b223d4cbb12edecf39202a5a53`

```dockerfile
ONBUILD RUN go-wrapper install
```

-	Created: Thu, 14 Jan 2016 17:16:46 GMT
-	Parent Layer: `bfbba38b8b997035e4eafb082c12da5707dddb2b66c5ca44f0b7ce7db103464e`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.6beta2-wheezy`

```console
$ docker pull library/golang@sha256:bb268a9ac34f20cad8def78cebdf65c58bc304f6032269128cd32e84a2ce9b30
```

-	Total Virtual Size: 620.9 MB (620889518 bytes)
-	Total v2 Content-Length: 201.1 MB (201073162 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `dd80b59716b4b142585cfebc93057c142a605b945ad218668e6b765b285cb9b2`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:17:12 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a41db96c34ec236b7b5434a4273fd7e92220ec04cb3450801941267be2ce9fa4`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:17:13 GMT
-	Parent Layer: `dd80b59716b4b142585cfebc93057c142a605b945ad218668e6b765b285cb9b2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7caa8d1d9476d44e21915ef38e58b042b86e3b0ae5c8e84156ed7ac510b5940d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:17:13 GMT
-	Parent Layer: `a41db96c34ec236b7b5434a4273fd7e92220ec04cb3450801941267be2ce9fa4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `85f0a3937ae99acd4d8e03de6965a6f0a8f11512bb8f4ada5df6ba80e90aa602`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:17:19 GMT
-	Parent Layer: `7caa8d1d9476d44e21915ef38e58b042b86e3b0ae5c8e84156ed7ac510b5940d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:8aec278a72a99bf618f2614136de2a5b3a9f33dd10dc5cdfccc3d63233da7773`
-	v2 Content-Length: 85.9 MB (85860597 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:34:53 GMT

#### `2b8dd2ec6ad1ae12b58db43d3d27332dd86d0771abb247bdfe6000aae84fee3d`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:17:23 GMT
-	Parent Layer: `85f0a3937ae99acd4d8e03de6965a6f0a8f11512bb8f4ada5df6ba80e90aa602`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d72a1e45ab1489a7ccf5c1712c33c88a4539cd90fa67143088d30c1937fac94b`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:17:24 GMT
-	Parent Layer: `2b8dd2ec6ad1ae12b58db43d3d27332dd86d0771abb247bdfe6000aae84fee3d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6907a9e522ac7f68086a8064f8fc9e3e08f64b4c922ffd8e47b4f30da092d3eb`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:17:25 GMT
-	Parent Layer: `d72a1e45ab1489a7ccf5c1712c33c88a4539cd90fa67143088d30c1937fac94b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:beec9ca94be34c90aeccb85e09104672a00303fb87f68367a6d0246e1024fe3c`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:34:04 GMT

#### `5d2f8b71a0e544c9c9b138944e32c588253b3f404633c578a8c68f9a82e94dca`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:17:26 GMT
-	Parent Layer: `6907a9e522ac7f68086a8064f8fc9e3e08f64b4c922ffd8e47b4f30da092d3eb`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d41466a4c2304f5ded254a75ddf537aec74bb44149296f69d27723364568c102`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:17:26 GMT
-	Parent Layer: `5d2f8b71a0e544c9c9b138944e32c588253b3f404633c578a8c68f9a82e94dca`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:97c0ef21fdebaac9cf4a47b36dbf2a6cf7e1d157c73b80ebea4c15e1e9f83d52`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:33:58 GMT

## `golang:1.6-wheezy`

```console
$ docker pull library/golang@sha256:8b6ba7118c7c4a304a0aec9daeb3dc4f005508958e62c0db919d5990f7a48f2c
```

-	Total Virtual Size: 620.9 MB (620889518 bytes)
-	Total v2 Content-Length: 201.1 MB (201073162 bytes)

### Layers (14)

#### `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`

```dockerfile
ADD file:0b9627ea84d3fc82bff7868a7f4b811eb6817e098c9597e09893bb8d1e02905a in /
```

-	Created: Thu, 07 Jan 2016 01:09:25 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:5e7f975cbeebaf47fcee32decf1ad5d337ad760ca194d42780615d383db07355`
-	v2 Content-Length: 37.2 MB (37184930 bytes)
-	v2 Last-Modified: Wed, 06 Jan 2016 23:31:57 GMT

#### `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 07 Jan 2016 01:09:28 GMT
-	Parent Layer: `68aefa3a05aa59fcd4e42132a9e9f2d04b0a42abd029b1574a48262d2ec2eee5`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:07 GMT
-	Parent Layer: `a525b4275c74fe83b8e12c2f8e6f4f6b2626d9c5a7d965e8d90f31184886278f`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:964f107790de57966e1f97caa099091fc27263c692cd980b12f43369c45617dd`
-	v2 Content-Length: 6.7 MB (6728545 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:58:13 GMT

#### `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 07 Jan 2016 01:32:37 GMT
-	Parent Layer: `c6c0ebdaaa2240ffed5e81191bbe8bcca3679301539c1fe1a96e0064bf04b3e9`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110024133 bytes)
-	v2 Blob: `sha256:841c40a00155695bb334330aa0577440f207bf5ac201c21c78271b1acd866bea`
-	v2 Content-Length: 37.4 MB (37365080 bytes)
-	v2 Last-Modified: Thu, 07 Jan 2016 01:59:26 GMT

#### `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		g++ \
		gcc \
		libc6-dev \
		make \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 08 Jan 2016 14:44:17 GMT
-	Parent Layer: `a8f09f07832879c9eeabb4ae60fe8903cdb9bf5848041a5a6520d6f321252678`
-	Docker Version: 1.8.3
-	Virtual Size: 90.8 MB (90804284 bytes)
-	v2 Blob: `sha256:cfb7bc0e452f32740ab19cddfe4c14afbdf96b60b92d78b4bb815ea77ed32d8c`
-	v2 Content-Length: 33.9 MB (33932308 bytes)
-	v2 Last-Modified: Mon, 11 Jan 2016 18:30:10 GMT

#### `dd80b59716b4b142585cfebc93057c142a605b945ad218668e6b765b285cb9b2`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:17:12 GMT
-	Parent Layer: `9eddf1f26a5c5281674d617148b38d403dd76cc9de92332e952be1c59dbb83df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a41db96c34ec236b7b5434a4273fd7e92220ec04cb3450801941267be2ce9fa4`

```dockerfile
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6beta2.linux-amd64.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:17:13 GMT
-	Parent Layer: `dd80b59716b4b142585cfebc93057c142a605b945ad218668e6b765b285cb9b2`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7caa8d1d9476d44e21915ef38e58b042b86e3b0ae5c8e84156ed7ac510b5940d`

```dockerfile
ENV GOLANG_DOWNLOAD_SHA256=7ddf9797c7baaac2c16eed1a8d42f9a446223301c7dc8771ea805f211828e6a5
```

-	Created: Thu, 14 Jan 2016 17:17:13 GMT
-	Parent Layer: `a41db96c34ec236b7b5434a4273fd7e92220ec04cb3450801941267be2ce9fa4`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `85f0a3937ae99acd4d8e03de6965a6f0a8f11512bb8f4ada5df6ba80e90aa602`

```dockerfile
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz \
	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:17:19 GMT
-	Parent Layer: `7caa8d1d9476d44e21915ef38e58b042b86e3b0ae5c8e84156ed7ac510b5940d`
-	Docker Version: 1.8.3
-	Virtual Size: 321.0 MB (320979392 bytes)
-	v2 Blob: `sha256:8aec278a72a99bf618f2614136de2a5b3a9f33dd10dc5cdfccc3d63233da7773`
-	v2 Content-Length: 85.9 MB (85860597 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:34:53 GMT

#### `2b8dd2ec6ad1ae12b58db43d3d27332dd86d0771abb247bdfe6000aae84fee3d`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:17:23 GMT
-	Parent Layer: `85f0a3937ae99acd4d8e03de6965a6f0a8f11512bb8f4ada5df6ba80e90aa602`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d72a1e45ab1489a7ccf5c1712c33c88a4539cd90fa67143088d30c1937fac94b`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:17:24 GMT
-	Parent Layer: `2b8dd2ec6ad1ae12b58db43d3d27332dd86d0771abb247bdfe6000aae84fee3d`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6907a9e522ac7f68086a8064f8fc9e3e08f64b4c922ffd8e47b4f30da092d3eb`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:17:25 GMT
-	Parent Layer: `d72a1e45ab1489a7ccf5c1712c33c88a4539cd90fa67143088d30c1937fac94b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:beec9ca94be34c90aeccb85e09104672a00303fb87f68367a6d0246e1024fe3c`
-	v2 Content-Length: 123.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:34:04 GMT

#### `5d2f8b71a0e544c9c9b138944e32c588253b3f404633c578a8c68f9a82e94dca`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:17:26 GMT
-	Parent Layer: `6907a9e522ac7f68086a8064f8fc9e3e08f64b4c922ffd8e47b4f30da092d3eb`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d41466a4c2304f5ded254a75ddf537aec74bb44149296f69d27723364568c102`

```dockerfile
COPY file:7e87b0ea22c04c4ebf8c516b8a68afbd30938d3a2cba2e4e91715a4b3cf5a73d in /usr/local/bin/
```

-	Created: Thu, 14 Jan 2016 17:17:26 GMT
-	Parent Layer: `5d2f8b71a0e544c9c9b138944e32c588253b3f404633c578a8c68f9a82e94dca`
-	Docker Version: 1.8.3
-	Virtual Size: 2.5 KB (2481 bytes)
-	v2 Blob: `sha256:97c0ef21fdebaac9cf4a47b36dbf2a6cf7e1d157c73b80ebea4c15e1e9f83d52`
-	v2 Content-Length: 1.4 KB (1355 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:33:58 GMT

## `golang:1.6beta2-alpine`

```console
$ docker pull library/golang@sha256:707b96a908887b9d700d433c2c3be2cb9ee74e529228902f9b5f9ce04b004919
```

-	Total Virtual Size: 282.1 MB (282089936 bytes)
-	Total v2 Content-Length: 71.6 MB (71643679 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `b4b946572a961c4dc8da7ec3ee1d2bf15df0ac4c2bd421953c49e854d3d50245`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:18:02 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e4742f0ffad52414d945c09bcc48c5f2dad0574b15944698f3ba59584f3d40be`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6beta2.src.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:18:02 GMT
-	Parent Layer: `b4b946572a961c4dc8da7ec3ee1d2bf15df0ac4c2bd421953c49e854d3d50245`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f96f491a4a2fef4d3a23434725535ac745030d9fd024c2272cbc4391b541d73b`

```dockerfile
ENV GOLANG_SRC_SHA256=8b23d15a3edf1d154ceea5e9ca6370fc60e7f57fb1c28aa8a44c40f8f3167c6d
```

-	Created: Thu, 14 Jan 2016 17:18:03 GMT
-	Parent Layer: `e4742f0ffad52414d945c09bcc48c5f2dad0574b15944698f3ba59584f3d40be`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `307fda318cd2f6e041e752dc4a433d967f016fc949ee20534efc9b62dd2c3d8f`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Thu, 14 Jan 2016 17:18:03 GMT
-	Parent Layer: `f96f491a4a2fef4d3a23434725535ac745030d9fd024c2272cbc4391b541d73b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4fa4cd25a94d37f193ecd267b1a84e1168831bed74708331126a85d953ba89c6`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:18:04 GMT
-	Parent Layer: `307fda318cd2f6e041e752dc4a433d967f016fc949ee20534efc9b62dd2c3d8f`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66bd0e400186615c9d2ac076878215c9213793b88b239b25d1cdc05f593c8b11`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Thu, 14 Jan 2016 17:18:05 GMT
-	Parent Layer: `4fa4cd25a94d37f193ecd267b1a84e1168831bed74708331126a85d953ba89c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bc75b9a1ecccd24d38f473d0bc57655ba0ce4a441592c6f4f292b5977a5e9598`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Thu, 14 Jan 2016 17:20:02 GMT
-	Parent Layer: `66bd0e400186615c9d2ac076878215c9213793b88b239b25d1cdc05f593c8b11`
-	Docker Version: 1.8.3
-	Virtual Size: 277.3 MB (277295997 bytes)
-	v2 Blob: `sha256:a44e9d1b30bc5c08816bbba90059ef013dffd07f640f52643dea1055cf076591`
-	v2 Content-Length: 69.3 MB (69324340 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:38:12 GMT

#### `71d764134685f1320f813cf4ab6cf15640cad941db8751028e3b8574b14e30c0`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:20:05 GMT
-	Parent Layer: `bc75b9a1ecccd24d38f473d0bc57655ba0ce4a441592c6f4f292b5977a5e9598`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c35517ee4ce2bd1be1f2487e6ac155c30c87f2dd25fc1f4428f8e8a55160e0af`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:20:05 GMT
-	Parent Layer: `71d764134685f1320f813cf4ab6cf15640cad941db8751028e3b8574b14e30c0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `994de2e4b92f19a8044272dd11faf50c1b23423b007287cebca72f3f1f439ecb`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:20:07 GMT
-	Parent Layer: `c35517ee4ce2bd1be1f2487e6ac155c30c87f2dd25fc1f4428f8e8a55160e0af`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:6b8fd754a56504721c1d49bf35e881bf06b1ce712c7d6a832147b5b70ce8de0e`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:37:26 GMT

#### `404ac12405e6ff8d998f3c9b1574d71f2b3bdfd12da01bba95dd27b8eb76e27d`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:20:08 GMT
-	Parent Layer: `994de2e4b92f19a8044272dd11faf50c1b23423b007287cebca72f3f1f439ecb`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `golang:1.6-alpine`

```console
$ docker pull library/golang@sha256:f8620b9d4fee07f062569674967cf30c1b007edef9e05b52caab2c761c7e2a9b
```

-	Total Virtual Size: 282.1 MB (282089936 bytes)
-	Total v2 Content-Length: 71.6 MB (71643679 bytes)

### Layers (12)

#### `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`

```dockerfile
ADD file:096dd6620d03d13136a6b3bf1228e35ad63d88a165af095e5d07e44db6ba740e in /
```

-	Created: Thu, 24 Dec 2015 15:25:46 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 4.8 MB (4793939 bytes)
-	v2 Blob: `sha256:8f4ec95ceaee9d0d795f5684db8edf87b944c54c0ea30c2395e1c7cd6a9509a8`
-	v2 Content-Length: 2.3 MB (2318929 bytes)
-	v2 Last-Modified: Thu, 24 Dec 2015 15:29:32 GMT

#### `b4b946572a961c4dc8da7ec3ee1d2bf15df0ac4c2bd421953c49e854d3d50245`

```dockerfile
ENV GOLANG_VERSION=1.6beta2
```

-	Created: Thu, 14 Jan 2016 17:18:02 GMT
-	Parent Layer: `340b2f9a264379f9f230de0af84330fc0b045d79e9b8d90f1558a447ddfb4538`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e4742f0ffad52414d945c09bcc48c5f2dad0574b15944698f3ba59584f3d40be`

```dockerfile
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6beta2.src.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:18:02 GMT
-	Parent Layer: `b4b946572a961c4dc8da7ec3ee1d2bf15df0ac4c2bd421953c49e854d3d50245`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f96f491a4a2fef4d3a23434725535ac745030d9fd024c2272cbc4391b541d73b`

```dockerfile
ENV GOLANG_SRC_SHA256=8b23d15a3edf1d154ceea5e9ca6370fc60e7f57fb1c28aa8a44c40f8f3167c6d
```

-	Created: Thu, 14 Jan 2016 17:18:03 GMT
-	Parent Layer: `e4742f0ffad52414d945c09bcc48c5f2dad0574b15944698f3ba59584f3d40be`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `307fda318cd2f6e041e752dc4a433d967f016fc949ee20534efc9b62dd2c3d8f`

```dockerfile
ENV GOLANG_BOOTSTRAP_VERSION=1.4.3
```

-	Created: Thu, 14 Jan 2016 17:18:03 GMT
-	Parent Layer: `f96f491a4a2fef4d3a23434725535ac745030d9fd024c2272cbc4391b541d73b`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4fa4cd25a94d37f193ecd267b1a84e1168831bed74708331126a85d953ba89c6`

```dockerfile
ENV GOLANG_BOOTSTRAP_URL=https://golang.org/dl/go1.4.3.src.tar.gz
```

-	Created: Thu, 14 Jan 2016 17:18:04 GMT
-	Parent Layer: `307fda318cd2f6e041e752dc4a433d967f016fc949ee20534efc9b62dd2c3d8f`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66bd0e400186615c9d2ac076878215c9213793b88b239b25d1cdc05f593c8b11`

```dockerfile
ENV GOLANG_BOOTSTRAP_SHA1=486db10dc571a55c8d795365070f66d343458c48
```

-	Created: Thu, 14 Jan 2016 17:18:05 GMT
-	Parent Layer: `4fa4cd25a94d37f193ecd267b1a84e1168831bed74708331126a85d953ba89c6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bc75b9a1ecccd24d38f473d0bc57655ba0ce4a441592c6f4f292b5977a5e9598`

```dockerfile
RUN set -ex \
	&& apk add --no-cache --virtual .build-deps \
		bash \
		ca-certificates \
		gcc \
		musl-dev \
		openssl \
		&& mkdir -p /usr/local/bootstrap \
	&& wget -q "$GOLANG_BOOTSTRAP_URL" -O golang.tar.gz \
	&& echo "$GOLANG_BOOTSTRAP_SHA1  golang.tar.gz" | sha1sum -c - \
	&& tar -C /usr/local/bootstrap -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/bootstrap/go/src \
	&& ./make.bash \
	&& export GOROOT_BOOTSTRAP=/usr/local/bootstrap/go \
		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz \
	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - \
	&& tar -C /usr/local -xzf golang.tar.gz \
	&& rm golang.tar.gz \
	&& cd /usr/local/go/src \
	&& ./make.bash \
		&& rm -rf /usr/local/bootstrap \
	&& apk del .build-deps
```

-	Created: Thu, 14 Jan 2016 17:20:02 GMT
-	Parent Layer: `66bd0e400186615c9d2ac076878215c9213793b88b239b25d1cdc05f593c8b11`
-	Docker Version: 1.8.3
-	Virtual Size: 277.3 MB (277295997 bytes)
-	v2 Blob: `sha256:a44e9d1b30bc5c08816bbba90059ef013dffd07f640f52643dea1055cf076591`
-	v2 Content-Length: 69.3 MB (69324340 bytes)
-	v2 Last-Modified: Thu, 14 Jan 2016 17:38:12 GMT

#### `71d764134685f1320f813cf4ab6cf15640cad941db8751028e3b8574b14e30c0`

```dockerfile
ENV GOPATH=/go
```

-	Created: Thu, 14 Jan 2016 17:20:05 GMT
-	Parent Layer: `bc75b9a1ecccd24d38f473d0bc57655ba0ce4a441592c6f4f292b5977a5e9598`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c35517ee4ce2bd1be1f2487e6ac155c30c87f2dd25fc1f4428f8e8a55160e0af`

```dockerfile
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 14 Jan 2016 17:20:05 GMT
-	Parent Layer: `71d764134685f1320f813cf4ab6cf15640cad941db8751028e3b8574b14e30c0`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `994de2e4b92f19a8044272dd11faf50c1b23423b007287cebca72f3f1f439ecb`

```dockerfile
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
```

-	Created: Thu, 14 Jan 2016 17:20:07 GMT
-	Parent Layer: `c35517ee4ce2bd1be1f2487e6ac155c30c87f2dd25fc1f4428f8e8a55160e0af`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:6b8fd754a56504721c1d49bf35e881bf06b1ce712c7d6a832147b5b70ce8de0e`
-	v2 Content-Length: 122.0 B
-	v2 Last-Modified: Thu, 14 Jan 2016 17:37:26 GMT

#### `404ac12405e6ff8d998f3c9b1574d71f2b3bdfd12da01bba95dd27b8eb76e27d`

```dockerfile
WORKDIR /go
```

-	Created: Thu, 14 Jan 2016 17:20:08 GMT
-	Parent Layer: `994de2e4b92f19a8044272dd11faf50c1b23423b007287cebca72f3f1f439ecb`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT
