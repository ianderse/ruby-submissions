### [Open Therapist Directory]

If this project gets selected, put **SELECTED** here

### Pitch

This project will provide a place for therapists and clients to connect for no charge to either the client or the therapist, as well as providing numerous resources for the low-income and homeless populations.

### Description

Provides clients and therapists with a platform to connect.  Also provides resources for homeless/low income populations to find mental health resources.  Possibly connects homeless population to therapists willing to donate their time for pro-bono work.  Perhaps it will also provide a google map with locations marked with therapists around a given location.
-I0: Providing homeless/low-income populations with resources based on this data set: http://store.samhsa.gov/developer
	- Plan to Have: Parses CSV file and provides listings by State
	- Nice to Have: Provides listings by City
	- Oh Shit: Has the basic framework of the site functioning.
-I1: Better search/results based on filtering (ie. by state, substance abuse treatment, etc.)
	- Plan to Have: Listings based on category.
	- Nice to Have: Fix the government and make them update their f'ing data sources and fix broken links.
	- Oh Shit: Make it prettier.
-I1.1: Ability to print out a PDF listing of all nearby treatment centers.
-I1.2: Ability to text a number and get a listing of nearby treatment centers (inteded for community members to help provide resources to those in need quickly).
	- Oh Shit: Just don't do it.
-I1.3: Mobile friendly.
-I2: Set up therapist listing portion of page.  Ability to add yourself as a therapist, therapists need to provide proof of education as a picture upload.
-I3: Ability to filter therapist listings by state,speciality,etc.
-I4: Enter your location on a map and show nearby therapists.
-Extension: Use some of the other data sets to show mental health reports state by state.

- Week 1: I0 and I1
- Week 2: I1.1, I1.2, I1.3 (or skip these and go to I2)
- Week 3: I2 and whatever else can be done.

### Target Audience

Low-income/Homeless population.
Therapists.
General population looking for mental health assistance.

### Integrations

* What OAuth provider makes sense for this audience? Facebook
* What Data.gov data or API will you use?  I will definitely use the treatment facility locator.  I would also like to use some of the stats to create interesting data sets if time permits.
- http://catalog.data.gov/dataset/mental-health-treatement-facilities-locator
- http://catalog.data.gov/dataset/state-by-state-behavioral-health-resources
- http://catalog.data.gov/dataset/physical-and-mental-health-condition-prevalence-and-comor
- http://catalog.data.gov/dataset/national-mental-health-services-survey-n-mhss-2010
- http://catalog.data.gov/dataset/national-and-state-estimates-on-prevalence-of-behavioral-health-conditions
- http://catalog.data.gov/dataset/designated-health-professional-shortage-areas
- http://www.apa.org/helpcenter/data-behavioral-health.aspx
- http://www.cdc.gov/mentalhealth/data_stats/depression.htm
- http://data.opencolorado.org/dataset/city-and-county-of-denver-affordable-housing-units
- http://data.opencolorado.org/dataset/city-and-county-of-denver-head-start-programs
- http://data.opencolorado.org/dataset/city-and-county-of-denver-hiv-healthcare-providers
* Any other integrations?
- http://store.samhsa.gov/developer
- http://aids.gov/locator/#api
- http://recoverymonth.gov/webservices/events.asmx?op=GetEventsByZip

My other ideas are just offshoots of this project and/or just trimming it down some.  I would love to work on something related to this, and I am open to suggestions, but I feel passionate about the pain points in the mental health field and feel this could contribute to the community.  As such, I have put up a placeholder rails project on a digital ocean droplet and registered the domain name: [Open Therapist Directory](http://www.opentherapistdirectory.com/)
