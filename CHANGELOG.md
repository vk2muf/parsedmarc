2.1.2
-----
- Rename `parsed_dmarc_forensic_reports_to_csv()` to
 `parsed_forensic_reports_to_csv()` to match other functions
- Rename `parsed_aggregate_report_to_csv()` to
 `parsed_aggregate_reports_to_csv()` to match other functions
- Use local time when generating the default email subject

2.1.1
-----
- Documentation fixes

2.1.0
-----
- Add `get_report_zip()` and `email_results()`
- Add support for sending report emails via the command line

2.0.1
-----
- Fix documentation
- Remove Python 2 code

2.0.0
-----
### New features
- Parse forensic reports
- Parse reports from IMAP inbox

### Changes
- Drop support for Python 2
- Command line output is always a JSON object containing the lists
  `aggregate_reports` and `forensic_reports`
- `-o`/`--output` option is now a path to an output directory, instead of an
  output file

1.1.0
-----
- Add `extract_xml()` and `human_timespamp_to_datetime` methods


1.0.5
-----
- Prefix public suffix and GeoIP2 database filenames with `.` 
- Properly format errors list in CSV output

1.0.3
-----
- Fix documentation formatting

1.0.2
-----
- Fix more packaging flaws

1.0.1
-----
- Fix packaging flaw

1.0.0
-----
- Initial release