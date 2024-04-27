# media-rust-pipe
- [X] PoC build of an `.rlib` *
- [ ] Integrate build with bazel
- [ ] Full `cxx` bindings for `ImageFrame`
- [ ] example `Calculator`

\* needs `protoc mediapipe/mediapipe/framework/formats/image_format.proto --cpp_out=.` and  `sudo cargo build` on Mac Os for bazel artifacts

Mediapipe release closest to first commit
https://github.com/ahirner/media-rust-pipe/commit/9171594f5b753ef7bb7ea8e9ec4127de2a19f13c
https://github.com/google/mediapipe/releases/tag/v0.7.5
	https://github.com/google/mediapipe/commit/5d028d923b52fd95bd49642a9a4a162f57ae260e
