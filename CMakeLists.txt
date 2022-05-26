include(hunter_add_version)
include(hunter_cacheable)
include(hunter_download)
include(hunter_pick_scheme)
hunter_add_version(
	PACKAGE_NAME
	banking
	VERSION
	1.0.0
	URL
	"https://github.com/sk3pta/lab05/archive/refs/tags/v1.0.0.tar.gz"
	SHA1
	4efa7f02b08548183457c99d8af6fb79a1391a77
)


hunter_pick_scheme(DEFAULT url_sha1_cmake)
hunter_cacheable(hunter_box_1)
hunter_download(PACKAGE_NAME hunter_box_1)
