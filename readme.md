#Wildfire Frame

Pre-Wireframe Structure

Features
  Report tbc
    First Page
    Functions
      What is the hazard?
        Fire
        Road Blocked, Power Line Down etc.
      Where is it?
        Offer saved locations, address or map functionality
      Is the reporter safe?
        Yes, No, I’m Not Sure.
    Actions
      Send report - data goes to reports.db
      Notify contacts on notification list
      Check if another user is close by (crossjoin reports.db with location data?) and notify them of a nearby report

    Second Page
      If not safe
        Tell the user to call 000 immediately (offer a link if on mobile?)
      If safe
        Advise the user to call 000 in addition to reporting
      If a Fire is Reported:
        Ask if the user intends to evacuate or stay and defend their property.
      If another hazard is reported:
        Offer a way for user to add information about hazard
        Depending on hazard, offer advice.

    Third Page
      If user is evacuating
        Open evacuation plan
        Notify them of any designated evacuation points.
        Offer evacuation locations that don’t go near reports OR Sentinel Hotspots etc.
      If user is staying
        Open defence plan

  Status tbc
    Text/Graphics
      Family List
        Marked as ok
        Recent reports
        Location tracking on/off
      Community List
        Incidents reported in x days (Last 24h, last 3 days, last week, etc.)
        Current Fire Danger Rating (also notify on home page is above x level
    Plugins/grabs
      Google Map of Reports
      Map of Sentinel Data
      Pager Feed from CFS
      CFS Incident and Event Map
      Twitter Feed?
      ABC Emergency Radio Feed?

  Plan
    Tabs:
      Family Locations (Last known location or tracked location
        Icon fa-child"\f1ae"
      Contact List (Saved contacts + Common emergency/bushfire contact numbers)
        Icon fa-phone"\f095"
      Saved location List (Option to connect to contact?)
      Evacuation Points
        Common Locations (Home, Work, School etc.)
        Icon - Home (/f015)
      Fire Plans
        Icon - fa-book"\f02d"   
      Stay and Defend Plan
        Icon - fa-fire-extinguisher"\f134"
      Evacuation Plan:
        Icon -fa-car"\f1b9"
      Practice your plans - as a sub-item in each plan?

  Learn
    Quizzes based on fire safety tbc
    Progress bar
    Comparison vs Other Communities

  Settings
    Username
    Email
    Phone No.
    Password
    Visibility/Location Settings
    Privacy Settings

  Help
    Videos of how to do things
    Text explanations of what things do
    Background information about resources etc.

  About
    About Wildfire (do the whole UI/pitchdeck thing)
    About Us

  Legal
    Disclaimers
    Licenses etc.
    Terms of Use
    Any other legal stuff that might come up

Styles
  Bootstrap?
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

    <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

  Font Awesome
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  Fonts



  <style>
  @import url('https://fonts.googleapis.com/css?family=Open+Sans:400,600,700');
  @import url('https://netdna.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.css');
