---
title: "`http_status` Dart Package: A Comprehensive Guide"
datePublished: Wed Feb 14 2024 17:10:48 GMT+0000 (Coordinated Universal Time)
cuid: clsm1t6yf00010ajq8mkhf65v
slug: dart-httpstatus-package
canonical: https://tech-andgar.me/posts/dart-http_status-package/
tags: dart, http-status, http-status-codes, httpstatus

---

# `http_status` Dart Package: A Comprehensive Guide

## Description

* **Constants:**[`http_status`](https://github.com/DartForge/http_status) provides convenient static constants representing all HTTP status codes defined in RFC 1945 (HTTP/1.0), RFC 2616 (HTTP/1.1), and RFC 2518 (WebDAV).
    
* **Clarity:** Each constant offers a clear name (e.g., `ok`, `notFound`, `forbidden`), making it easy to understand the meaning of a status code at a glance.
    
* **Information:** Constants also provide a concise description of the status code, which can be helpful in debugging or understanding API responses.
    

## Codes

| Code | Http Status Name | Http Status (v1.x - v2.x Deprecated) | Http Status (v2.x - v3.x) |
| --- | --- | --- | --- |
| 100 | Continue | Continue / CONTINUE | continue\_ |
| 101 | Switching Protocols | Switching\_Protocols / SWITCHING\_PROTOCOLS | switchingProtocols |
| 102 | Processing | Processing / PROCESSING | processing |
| 103 | Early Hints | \- | earlyHints |
| 200 | OK | Ok / OK | ok |
| 201 | Created | Created / CREATED | created |
| 202 | Accepted | Accepted / ACCEPTED | accepted |
| 203 | Non Authoritative Information | NonAuthoritative\_Information / NON\_AUTHORITATIVE\_INFORMATION | nonAuthoritativeInformation |
| 204 | No Content | No\_Content / NO\_CONTENT | noContent |
| 205 | Reset Content | Reset\_Content / RESET\_CONTENT | resetContent |
| 206 | Partial Content | Partial\_Content / PARTIAL\_CONTENT | partialContent |
| 207 | Multi-Status | MultiStatus / MULTISTATUS | multiStatus |
| 208 | Already Reported | Already\_Reported / ALREADY\_REPORTED | alreadyReported |
| 226 | I'M Used | IM\_Used / IM\_USED | imUsed |
| 300 | Multiple Choices | Multiple\_Choices / MULTIPLE\_CHOICES | multipleChoices |
| 301 | Moved Permanently | Moved\_Permanently / MOVED\_PERMANENTLY | movedPermanently |
| 302 | Found / Moved Temporarily | Found / Moved\_Temporarily / FOUND / MOVED\_TEMPORARILY | found / movedTemporarily |
| 303 | See Other | See\_Other / SEE\_OTHER | seeOther |
| 304 | Not Modified | Not\_Modified / NOT\_MODIFIED | notModified |
| 305 | Use Proxy | Use\_Proxy / USE\_PROXY | useProxy |
| 307 | Temporary Redirect | Temporary\_Redirect / TEMPORARY\_REDIRECT | temporaryRedirect |
| 308 | Permanent Redirect | Permanent\_Redirect / PERMANENT\_REDIRECT | permanentRedirect |
| 400 | Bad Request | Bad\_Request / BAD\_REQUEST | badRequest |
| 401 | Unauthorized | Unauthorized / UNAUTHORIZED | unauthorized |
| 402 | Payment Required | Payment\_Required / PAYMENT\_REQUIRED | paymentRequired |
| 403 | Forbidden | Forbidden / FORBIDDEN | forbidden |
| 404 | Not Found | Not\_Found / NOT\_FOUND | notFound |
| 405 | Method Not Allowed | Method\_Not\_Allowed / METHOD\_NOT\_ALLOWED | methodNotAllowed |
| 406 | Not Acceptable | Not\_Acceptable / NOT\_ACCEPTABLE | notAcceptable |
| 407 | Proxy Authentication Required | Proxy\_Authentication\_Required / PROXY\_AUTHENTICATION\_REQUIRED | proxyAuthenticationRequired |
| 408 | Request Timeout | Request\_Timeout / REQUEST\_TIMEOUT | requestTimeout |
| 409 | Conflict | Conflict / CONFLICT | conflict |
| 410 | Gone | Gone / GONE | gone |
| 411 | Length Required | Length\_Required / LENGTH\_REQUIRED | lengthRequired |
| 412 | Precondition Failed | Precondition\_Failed / PRECONDITION\_FAILED | preconditionFailed |
| 413 | Request Entity Too Large | Payload\_Too\_Large / PAYLOAD\_TOO\_LARGE / Request\_Entity\_Too\_Large / REQUEST\_ENTITY\_TOO\_LARGE | requestEntityTooLarge |
| 414 | Request-URI Too Long | RequestURI\_Too\_Long / REQUESTURI\_TOO\_LONG / Request\_Uri\_Too\_Long / REQUEST\_URI\_TOO\_LONG | requestUriTooLong |
| 415 | Unsupported Media Type | Unsupported\_Media\_Type / UNSUPPORTED\_MEDIA\_TYPE | unsupportedMediaType |
| 416 | Requested Range Not Satisfiable | Requested\_Range\_Not\_Satisfiable / REQUESTED\_RANGE\_NOT\_SATISFIABLE | requestedRangeNotSatisfiable |
| 417 | Expectation Failed | Expectation\_Failed / EXPECTATION\_FAILED | expectationFailed |
| 418 | I'm a teapot | \- | imATeapot |
| 419 | Insufficient Space on Resource | \- | insufficientSpaceOnResource |
| 420 | Method Failure | \- | methodFailure |
| 421 | Misdirected Request | Misdirected\_Request / MISDIRECTED\_REQUEST | misdirectedRequest |
| 422 | Unprocessable Entity | Unprocessable\_Entity / UNPROCESSABLE\_ENTITY | unprocessableEntity |
| 423 | Locked | Locked / LOCKED | locked |
| 424 | Failed Dependency | Failed\_Dependency / FAILED\_DEPENDENCY | failedDependency |
| 426 | Upgrade Required | Upgrade\_Required / UPGRADE\_REQUIRED | upgradeRequired |
| 428 | Precondition Required | Precondition\_Required / PRECONDITION\_REQUIRED | preconditionRequired |
| 429 | Too Many Requests | Too\_Many\_Requests / TOO\_MANY\_REQUESTS | tooManyRequests |
| 431 | Request Header Fields Too Large | Request\_Header\_Fields\_Too\_Large / REQUEST\_HEADER\_FIELDS\_TOO\_LARGE | requestHeaderFieldsTooLarge |
| 444 | Connection Closed Without Response | Connection\_Closed\_Without\_Response / CONNECTION\_CLOSED\_WITHOUT\_RESPONSE | connectionClosedWithoutResponse |
| 451 | Unavailable For Legal Reasons | Unavailable\_For\_Legal\_Reasons / UNAVAILABLE\_FOR\_LEGAL\_REASONS | unavailableForLegalReasons |
| 499 | Client Closed Request | Client\_Closed\_Request / CLIENT\_CLOSED\_REQUEST | clientClosedRequest |
| 500 | Internal Server Error | Internal\_Server\_Error / INTERNAL\_SERVER\_ERROR | internalServerError |
| 501 | Not Implemented | Not\_Implemented / NOT\_IMPLEMENTED | notImplemented |
| 502 | Bad Gateway | Bad\_Gateway / BAD\_GATEWAY | badGateway |
| 503 | Service Unavailable | Service\_Unavailable / SERVICE\_UNAVAILABLE | serviceUnavailable |
| 504 | Gateway Timeout | Gateway\_Timeout / GATEWAY\_TIMEOUT | gatewayTimeout |
| 505 | HTTP Version Not Supported | HTTP\_Version\_Not\_Supported / HTTP\_VERSION\_NOT\_SUPPORTED | httpVersionNotSupported |
| 506 | Variant Also Negotiates | Variant\_Also\_Negotiates / VARIANT\_ALSO\_NEGOTIATES | variantAlsoNegotiates |
| 507 | Insufficient Storage | Insufficient\_Storage / INSUFFICIENT\_STORAGE | insufficientStorage |
| 508 | Loop Detected | Loop\_Detected / LOOP\_DETECTED | loopDetected |
| 510 | Not Extended | Not\_Extended / NOT\_EXTENDED | notExtended |
| 511 | Network Authentication Required | Network\_Authentication\_Required / NETWORK\_AUTHENTICATION\_REQUIRED | networkAuthenticationRequired |
| 599 | Network Connect Timeout Error | Network\_Connect\_Timeout\_Error / NETWORK\_CONNECT\_TIMEOUT\_ERROR | networkConnectTimeoutError |

A library for debugging and displaying http status codes. Includes 63 status codes, messages and desciptions sourced from the official spec [https://tools.ietf.org/html/rfc723](https://tools.ietf.org/html/rfc723) and [https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/)

## Key Features

* **Clean API:** The interface is straightforward and intuitive, simplifying the use of status codes in your Dart applications.
    
* **Readability:** Constant names and descriptions enhance code clarity and maintainability.
    
* **Type Safety:** Static constants prevent typos and accidental use of incorrect status codes.
    
* **Completeness:** Extensive coverage of HTTP status codes ensures reliable handling of various response scenarios.
    

## Installation

Add the following dependency to your Dart project's `pubspec.yaml`:

```yaml
dependencies:
  http_status: <latest_version> # ^2.1.0 is last version compatible with v1.x
```

## Usage

1. **Import:**
    
    ```dart
    import 'package:http_status/http_status.dart';
    ```
    
2. **Access Constants:**
    
    ```dart
    print(HttpStatusCode.ok);          // Output: 200
    print(HttpStatus.ok.name);         // Output: OK
    print(HttpStatus.ok.code);         // Output: 200
    print(HttpStatus.ok.description);  // Output: The request was fulfilled.
    ```
    
3. **Check Statuses:**
    
    ```dart
    if (res.statusCode.isSuccessfulHttpStatusCode) {
      // Handle successful response
    } else if (res.statusCode.isClientErrorHttpStatusCode) {
      // Handle client error
    } else {
      // Handle other errors
    }
    ```
    
4. **Convert from Int:**
    
    ```dart
    final httpStatus = HttpStatus.fromCode(res.statusCode);
    ```
    

## Example

```dart
import 'package:http/http.dart' as http;
import 'package:http_status/http_status.dart';

final url = 'https://api.example.com/data';

Future<void> fetchData() async {
  try {
    final response = await http.get(Uri.parse(url));

     if (res.statusCode.isClientErrorHttpStatusCode) { // HTTP status code 400 - 499
       // Handle client error
     } else if (response.statusCode == HttpStatusCode.ok) {
      final data = response.body;
      // Process successful response
    } else {
      print('Error: ${response.statusCode}');
      // Handle errors gracefully
    }
  } catch (error) {
    print('Error: $error');
  }
}

void main() {
  fetchData();
}
```

This code fetches data from an API and checks the HTTP status code of the response. Based on the code, you can take appropriate actions depending on the outcome.

## Additional Tips

* Use meaningful variable names (e.g., `data` instead of `httpStatus.description`).
    
* Consider using `try-catch` blocks to handle network errors gracefully.
    
* Refer to the [`http_status`](https://github.com/DartForge/http_status) documentation for the latest information and additional features.
    

I hope this comprehensive valuable insights into using the [`http_status`](https://github.com/DartForge/http_status) package in your Dart projects!