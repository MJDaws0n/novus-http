# http

HTTP client and server primitives built on net.

This document is auto-generated from the function signatures in this repository. 
It lists every public function the library exposes.

## Install

```sh
nox pull http
```

## Import

```novus
import lib/http http;
```

## Functions

### `hex_digit_val`

```novus
fn hex_digit_val(ch: i32) -> i32;
```
_Defined in: `darwin_arm64.nov`_

### `http_accept`

```novus
fn http_accept(server_fd: i32) -> i32;
```
_Defined in: `darwin_arm64.nov`_

### `http_content_type`

```novus
fn http_content_type(path: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_body`

```novus
fn http_get_body(request: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_header`

```novus
fn http_get_header(request: str, name: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_method`

```novus
fn http_get_method(request: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_path`

```novus
fn http_get_path(request: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_path_only`

```novus
fn http_get_path_only(path: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_get_query_string`

```novus
fn http_get_query_string(path: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_listen`

```novus
fn http_listen(port: i32) -> i32;
```
_Defined in: `darwin_arm64.nov`_

### `http_read_body_small`

```novus
fn http_read_body_small(client_fd: i32, content_length: i32) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_read_headers_only`

```novus
fn http_read_headers_only(client_fd: i32) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_read_request`

```novus
fn http_read_request(client_fd: i32) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_send`

```novus
fn http_send(client_fd: i32, status_code: i32, status_text: str, content_type: str, body: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_404`

```novus
fn http_send_404(client_fd: i32) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_405`

```novus
fn http_send_405(client_fd: i32) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_500`

```novus
fn http_send_500(client_fd: i32, msg: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_html`

```novus
fn http_send_html(client_fd: i32, html: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_json`

```novus
fn http_send_json(client_fd: i32, json: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_options`

```novus
fn http_send_options(client_fd: i32) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_send_text`

```novus
fn http_send_text(client_fd: i32, text: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_serve_file`

```novus
fn http_serve_file(client_fd: i32, file_path: str) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `http_status_line`

```novus
fn http_status_line(code: i32) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `http_url_decode`

```novus
fn http_url_decode(s: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_escape`

```novus
fn json_escape(s: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_get_value`

```novus
fn json_get_value(json: str, key: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_object_1`

```novus
fn json_object_1(k1: str, v1: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_object_2`

```novus
fn json_object_2(k1: str, v1: str, k2: str, v2: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_object_3`

```novus
fn json_object_3(k1: str, v1: str, k2: str, v2: str, k3: str, v3: str) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `json_string`

```novus
fn json_string(key: str, value: str) -> str;
```
_Defined in: `darwin_arm64.nov`_
