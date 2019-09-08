# timezoneStuff
why you so complex mr timezone

Site built on Discourse, having wordpress plugins, having eventOn for events
EventOn events show events in UTC timezone only, so here is the code to also show local (to browser/user) time of the event

Need such an html (to fetch data from <eventon meta> tag something for start and end date/times) that will contain something like:
<div class="evo_event_schema"...>
<meta itemprop="startDate" content="2019-12-25T00:00">
<meta itemprop="endDate" content="2020-1-20T12:00">
<meta itemprop="eventStatus" content="on-schedule">
...</div>

See: https://dev.theputtytribe.com/events/utc-event-by-harsh/