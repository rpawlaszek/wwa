 **Calendars**

 CAL2JD				Gregorian calendar to Julian Day number
 EPB				Julian Date to Besselian Epoch
 EPB2JD				Besselian Epoch to Julian Date
 EPJ				Julian Date to Julian Epoch
 EPJ2JD				Julian Epoch to Julian Date
 JD2CAL				Julian Date to Gregorian year, month, day, fraction
 JDCALF				Julian Date to Gregorian date for formatted output

 **Astrometry**

 AB					apply stellar aberration
 APCG				prepare for ICRS <-> GCRS, geocentric, special
 APCG13				prepare for ICRS <-> GCRS, geocentric
 APCI				prepare for ICRS <-> CIRS, terrestrial, special
 APCI13				prepare for ICRS <-> CIRS, terrestrial
 APCO				prepare for ICRS <-> observed, terrestrial, special
 APCO13				prepare for ICRS <-> observed, terrestrial
 APCS				prepare for ICRS <-> CIRS, space, special
 APCS13				prepare for ICRS <-> CIRS, space
 APER				insert ERA into context
 APER13				update context for Earth rotation
 APIO				prepare for CIRS <-> observed, terrestrial, special
 APIO13				prepare for CIRS <-> observed, terrestrial
 ATCI13				catalog -> CIRS
 ATCIQ				quick ICRS -> CIRS
 ATCIQN				quick ICRS -> CIRS, multiple deflections
 ATCIQZ				quick astrometric ICRS -> CIRS
 ATCO13				ICRS -> observed
 ATIC13				CIRS -> ICRS
 ATICQ				quick CIRS -> ICRS
 ATCIQN				quick CIRS -> ICRS, multiple deflections
 ATIO13				CIRS -> observed
 ATIOQ				quick CIRS -> observed
 ATOC13				observed -> astrometric ICRS
 ATOI13				observed -> CIRS
 ATOIQ				quick observed -> CIRS
 LD					light deflection by a single solar-system body
 LDN				light deflection by multiple solar-system bodies
 LDSUN				light deflection by the Sun
 PMPX				apply proper motion and parallax
 PVTOB				observatory position and velocity
 REFCO				refraction constants
 PMSAFE				apply proper motion, with zero-parallax precautions
 STARPM				apply proper motion

 **Time scales**

 D2DTF				format 2-part JD for output
 DAT				Delta(AT) (=TAI-UTC) for a given UTC date
 DTDB				TDB-TT
 DTF2D				encode time and date fields into 2-part JD
 TAITT				TAI to TT
 TAIUT1				TAI to UT1
 TAIUTC				TAI to UTC
 TCBTDB				TCB to TDB
 TCGTT				TCG to TT
 TDBTCB				TDB to TCB
 TDBTT				TDB to TT
 TTTAI				TT to TAI
 TTTCG				TT to TCG
 TTTDB				TT to TDB
 TTUT1				TT to UT1
 UT1TAI				UT1 to TAI
 UT1TT				UT1 to TT
 UT1UTC				UT1 to UTC
 UTCTAI				UTC to TAI
 UTCUT1				UTC to UT1

 **Earth rotation angle and sidereal time**

 EE00				equation of the equinoxes, IAU 2000
 EE00A				equation of the equinoxes, IAU 2000A
 EE00B				equation of the equinoxes, IAU 2000B
 EE06A				equation of the equinoxes, IAU 2006/2000A
 EECT00				equation of the equinoxes complementary terms, IAU 2000
 EQEQ94				equation of the equinoxes, IAU 1994
 ERA00				Earth rotation angle, IAU 2000
 GMST00				Greenwich mean sidereal time, IAU 2000
 GMST06				Greenwich mean sidereal time, IAU 2006
 GMST82				Greenwich mean sidereal time, IAU 1982
 GST00A				Greenwich apparent sidereal time, IAU 2000A
 GST00B				Greenwich apparent sidereal time, IAU 2000B
 GST06				Greenwich apparent ST, IAU 2006, given NPB matrix
 GST06A				Greenwich apparent sidereal time, IAU 2006/2000A
 GST94				Greenwich apparent sidereal time, IAU 1994

 **Ephemerides (limited precision)**

 EPV00				Earth position and velocity
 PLAN94				major-planet position and velocity

 **Precession, nutation, polar motion**

 BI00				frame bias components, IAU 2000
 BP00				frame bias and precession matrices, IAU 2000
 BP06				frame bias and precession matrices, IAU 2006
 BPN2XY				extract CIP X,Y coordinates from NPB matrix
 C2I00A				celestial-to-intermediate matrix, IAU 2000A
 C2I00B				celestial-to-intermediate matrix, IAU 2000B
 C2I06A				celestial-to-intermediate matrix, IAU 2006/2000A
 C2IBPN				celestial-to-intermediate matrix, given NPB matrix, IAU 2000
 C2IXY				celestial-to-intermediate matrix, given X,Y, IAU 2000
 C2IXYS				celestial-to-intermediate matrix, given X,Y and s
 C2T00A				celestial-to-terrestrial matrix, IAU 2000A
 C2T00B				celestial-to-terrestrial matrix, IAU 2000B
 C2T06A				celestial-to-terrestrial matrix, IAU 2006/2000A
 C2TCIO				form CIO-based celestial-to-terrestrial matrix
 C2TEQX				form equinox-based celestial-to-terrestrial matrix
 C2TPE				celestial-to-terrestrial matrix given nutation, IAU 2000
 C2TXY				celestial-to-terrestrial matrix given CIP, IAU 2000
 EO06A				equation of the origins, IAU 2006/2000A
 EORS				equation of the origins, given NPB matrix and s
 FW2M				Fukushima-Williams angles to r-matrix
 FW2XY				Fukushima-Williams angles to X,Y
 NUM00A				nutation matrix, IAU 2000A
 NUM00B				nutation matrix, IAU 2000B
 NUM06A				nutation matrix, IAU 2006/2000A
 NUMAT				form nutation matrix
 NUT00A				nutation, IAU 2000A
 NUT00B				nutation, IAU 2000B
 NUT06A				nutation, IAU 2006/2000A
 NUT80				nutation, IAU 1980
 NUTM80				nutation matrix, IAU 1980
 OBL06				mean obliquity, IAU 2006
 OBL80				mean obliquity, IAU 1980
 PB06				zeta,z,theta precession angles, IAU 2006, including bias
 PFW06				bias-precession Fukushima-Williams angles, IAU 2006
 PMAT00				precession matrix (including frame bias), IAU 2000
 PMAT06				PB matrix, IAU 2006
 PMAT76				precession matrix, IAU 1976
 PN00				bias/precession/nutation results, IAU 2000
 PN00A				bias/precession/nutation, IAU 2000A
 PN00B				bias/precession/nutation, IAU 2000B
 PN06				bias/precession/nutation results, IAU 2006
 PN06A				bias/precession/nutation results, IAU 2006/2000A
 PNM00A				classical NPB matrix, IAU 2000A
 PNM00B				classical NPB matrix, IAU 2000B
 PNM06A				classical NPB matrix, IAU 2006/2000A
 PNM80				precession/nutation matrix, IAU 1976/1980
 P06E				precession angles, IAU 2006, equinox based
 POM00				polar motion matrix
 PR00				IAU 2000 precession adjustments
 PREC76				accumulated precession angles, IAU 1976
 S00				the CIO locator s, given X,Y, IAU 2000A
 S00A				the CIO locator s, IAU 2000A
 S00B				the CIO locator s, IAU 2000B
 S06				the CIO locator s, given X,Y, IAU 2006
 S06A				the CIO locator s, IAU 2006/2000A
 SP00				the TIO locator s', IERS 2003
 XY06				CIP, IAU 2006/2000A, from series
 XYS00A				CIP and s, IAU 2000A
 XYS00B				CIP and s, IAU 2000B
 XYS06A				CIP and s, IAU 2006/2000A

 **Fundamental arguments for nutation etc.**

 FAD03				mean elongation of the Moon from the Sun
 FAE03				mean longitude of Earth
 FAF03				mean argument of the latitude of the Moon
 FAJU03				mean longitude of Jupiter
 FAL03				mean anomaly of the Moon
 FALP03				mean anomaly of the Sun
 FAMA03				mean longitude of Mars
 FAME03				mean longitude of Mercury
 FANE03				mean longitude of Neptune
 FAOM03				mean longitude of the Moon's ascending node
 FAPA03				general accumulated precession in longitude
 FASA03				mean longitude of Saturn
 FAUR03				mean longitude of Uranus
 FAVE03				mean longitude of Venus

 **Star space motion**

 PVSTAR				space motion pv-vector to star catalog data
 STARPV				star catalog data to space motion pv-vector

 **Star catalog conversions**

 FK52H				transform FK5 star data into the Hipparcos system
 FK5HIP				FK5 to Hipparcos rotation and spin
 FK5HZ				FK5 to Hipparcos assuming zero Hipparcos proper motion
 H2FK5				transform Hipparcos star data into the FK5 system
 HFK5Z				Hipparcos to FK5 assuming zero Hipparcos proper motion

 **Galactic coordinates**

 G2ICRS    transform IAU 1958 galactic coordinates to ICRS
 ICRS2G    transform ICRS coordinates to IAU 1958 Galactic

 **Geodetic/geocentric**

 EFORM				a,f for a nominated Earth reference ellipsoid
 GC2GD				geocentric to geodetic for a nominated ellipsoid
 GC2GDE				geocentric to geodetic given ellipsoid a,f
 GD2GC				geodetic to geocentric for a nominated ellipsoid
 GD2GCE				geodetic to geocentric given ellipsoid a,f


 **Obsolete**

 C2TCEO				former name of C2TCIO
