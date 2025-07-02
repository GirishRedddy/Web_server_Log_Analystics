WEB Server Logistics is a Python-based tool for parsing and transforming Apache access logs into structured JSON format. It extracts key request metadata including method, URL, protocol, status codes, user agent details, and more. Ideal for log analysis, monitoring, and feeding into analytics or observability pipelines.

Features
Parses Apache access logs using apachelogs library

Extracts HTTP method, URL, protocol, status, and user agent details

Enhances logs by structuring data into clean key-value pairs

Drops redundant fields for cleaner output

Supports additional parsing of user-agent strings using httpagentparser

Dependencies
Python 3.7+

apachelogs

httpagentparser
