---
title: "`http_status` Paquete de Dart: Una Guía Completa"
seoTitle: "http_status Paquete de Dart: Una Guía Completa"
seoDescription: "http_status Paquete de Dart: Una Guía Completa
Constantes que enumeran los códigos de estado HTTP en Dart. Se soportan todos los códigos de estado definidos"
datePublished: Wed Feb 14 2024 17:10:47 GMT+0000 (Coordinated Universal Time)
cuid: clsm1t60b00000ajq6mmkhu4p
slug: dart-httpstatus-paquete
canonical: https://tech-andgar.me/es/posts/dart-http_status-package/
tags: dart, http-status, http-status-codes

---

# [`http_status`](https://github.com/DartForge/http_status) Paquete de Dart: Una Guía Completa

## Descripción

* **Constantes:**[`http_status`](https://github.com/DartForge/http_status) proporciona constantes estáticas que representan todos los códigos de estado HTTP definidos en RFC 1945 (HTTP/1.0), RFC 2616 (HTTP/1.1), y RFC 2518 (WebDAV).
    
* **Claridad:** Cada constante ofrece un nombre claro (por ejemplo, `ok`, `notFound`, `forbidden`), facilitando la comprensión del significado de un código de estado de un vistazo.
    
* **Información:** Las constantes también ofrecen una descripción concisa del código de estado, que puede ser útil para depurar o entender las respuestas de la API.
    

## Códigos de estado HTTP

| Código | Nombre de estado HTTP | `http_status` (v1.x - v2.x Deprecated \[obsoleto\]) | `http_status` (v2.x - v3.x) |
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

Una librería Dart para debuguear y mostrar códigos de estado http. Incluye 63 códigos de estado, mensajes y descripciones extraídos de las especificaciones oficiales [https://tools.ietf.org/html/rfc723](https://tools.ietf.org/html/rfc723) y [https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/)

## Características principales

* API limpia: La interfaz es sencilla e intuitiva, simplificando el uso de códigos de estado en sus aplicaciones Dart.
    
* Legibilidad: Los nombres y descripciones de las constantes mejoran la claridad del código y su mantenimiento.
    
* Seguridad tipográfica: Las constantes estáticas evitan errores tipográficos y el uso accidental de códigos de estado incorrectos.
    
* Completitud: Una amplia cobertura de los códigos de estado HTTP asegura un manejo fiable de varios escenarios de respuesta.
    

## Instalación

Continúe este artículo en mi blog personal [aquí](https://tech-andgar.me/es/posts/dart-http_status-package/).