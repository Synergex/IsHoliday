# IsHoliday<br />
**Created Date:** 2/19/2010<br />
**Last Updated:** 10/13/2010<br />
**Description:** IsHoliday() is a static method that will execute a remote web service and then return a status to determine if the passed date is a public holiday for the passed country code. (Update for Synergy 9.5 compatibility)<br />
**Platforms:** Windows; Unix; OpenVMS<br />
**Products:** Synergy DBL; HTTP API; XML API<br />
**Minimum Version:** 9.3.1<br />
**Author:** Richard Morris
<hr>

**Additional Information:**
Usage:

begin
data b,boolean
data d,d8,20100215
b=SynPSG.DateFunctions.IsHoliday(d, synpsg.CountryCode.UnitedStates)
;;if b == true the day is a holiday.
end
