These examples are from the apcupsd source, apcupsd is licensed under the GPLv2, although it seems unlikely that these examples would be
copyrightable. Modifications have been made to allow successful tests, such as changing the date/time format (timezone names can't reliably be
converted into offsets, so chrono returns an error), and changing old units like "Percent Load Capacity" to the current units like "Percent" in the
current version of apcupsd. Some lines were also removed, since previous versions of apcupsd seem to have output "N/A", while the current version
simply omits the line instead.
