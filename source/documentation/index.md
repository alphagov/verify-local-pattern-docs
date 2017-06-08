# Local government service patterns

These guidance pages are for people who work in local government. They outline best practice for delivering digital services.

The service patterns have been designed collaboratively by GDS and the councils involved in the <a href="http://www.localdigitalcoalition.uk/product/extension-of-gov-uk-verify-to-local-government-pilot/">Verify Local pilots</a>. The patterns are based on <a href="https://userresearch.blog.gov.uk/2017/02/14/collaborative-user-research-for-verifylocal-discovery/">user research done in Discovery</a>, and are actively being iterated on based on research with real users in Alpha.

To feedback on these patterns, <a href="https://github.com/alphagov/verify-local-patterns/blob/master/CONTRIBUTING.md">open an issue on Github</a>.


# Apply for a resident's parking permit

## Example service
<p>
	While reading the service pattern description, explore <a href="parking-permit/example-service/start-page">the example council service</a>.
</p>

## What is the user need?
<p>
		Residents need a place to park their car near their home. Parking permit services make sure there are parking spaces available for residents. They make it illegal to park in some areas without a permit.
</p>
<p>
	We recommend putting users first when designing your parking permit service.
</p>
<p><a href="/service-patterns/parking-permit/user-research/discovery">Understand other user needs for this service</a></p>

## What does your service need from users to deliver this service?
<p>Depending on your local authority's needs, the user may be asked to provide:</p>
<ul class="list list-bullet">
	<li>
		the postcode of the area where they want to park
	</li>
	<li>
			proof they live in the area
	</li>
	<li>
			the registration number of the vehicle to be permitted
	</li>
	<li>
			payment (supports the cost of the service and may vary from council to council and within the service, depending on for example vehicle and parking zone)
	</li>
</ul>

## What is the user journey?

These are the steps users should go through.

### 1. Awareness

Users should find out about the parking permits service before they need to park their car. This could be through:

 - council messaging when they sign up for council tax payments
 - estate agent information when they buy their house
 - street signage

Your service needs to make sure correct information is being provided through all channels within your control.

### 2. Finding the right council

When the user knows they need a permit, they need to get to the right council's website to apply. Users might start by typing 'parking permit' into a search engine, or going to the website of the council where they think they need a permit.

#### Search engine

<a href="https://www.gov.uk/parking-permit">The GOV.UK parking permits page</a> is the top result in most search engines. It should send users to the right council's website when they enter their postcode. Your service needs to make sure the postcodes it provides services for are linked to the right page on their website and email any corrections to <a href="mailto:local-direct-admin@digital.cabinet-office.gov.uk">local-direct-admin@digital.cabinet-office.gov.uk</a>.

#### Council website

Users may also go straight to the website for the council they think they need to get a permit from. This makes it very important for your service's webpage to clearly state which area your parking permit service covers – as the user may be in the wrong place.

### 3. Parking start page

Some users may not go through the two steps above. They may arrive on your council's website with a need to park, but no knowledge that they need a permit. So it's important to explain they may need a permit.

<a href="parking-permit/example-service/start-page">Explore the example council service start page</a>

<a href="user-research/discovery">Access related user research</a>

### 4. Routing to the right boundary
You need to find out where the user wants to park your service can:

 - give the user a permit for the right parking boundary
 - let the user know if there are no permits available for the area where they want to park
 - check the user is a resident in the parking boundary where they want to park

 The best way to do this is through a postcode lookup tool, as this is the easiest and fastest way for users to find and understand information they need about where they can park.

 It should be done at this early point in the user journey so that the user doesn't go through unnecessary effort.

 <a href="parking-permit/example-service/check-boundary">Explore the where do you want to park example council page</a>

<a href="user-research/discovery">Access related user research</a>

At this point your online service should also check if there are permits available in the area the user wants to park in. If permits are available, move the user onto the next step. If not, the council should tell the user what their alternative options are, based on the nearest boundaries with permits available.

<a href="parking-permit/example-service/no-permits">Explore the no permits available example council page</a>

<a href="user-research/discovery">Access related user research</a>

### 5. Picking the right permit type

When the council knows where the user wants to park and that permits are available, they can tell the user about the parking boundary and ask if they are a resident of that area.

<a href="parking-permit/example-service/resident-choice">Explore the resident or visitor example council page</a>

<a href="user-research/discovery">Access related user research</a>

### 6. Resident's start page

Now the user is in the right place, this page should communicate:

 - types of permit users can apply for (if applicable)
 - permit eligibility requirements
 - where the permit they are applying for will allow them to park
 - at what time the permit they are applying for will allow them to park
 - how much the permit will cost
 - how long the permit is valid for
 - what information they need about the car, for example vehicle registration number
 - how long the process usually takes
 - what to do if they need assistance with the application
if the service differs from this pattern, include any other information the user needs to provide

<a href="parking-permit/example-service/resident-start">Explore the example council resident's start page</a>

<a href="user-research/discovery">Access related user research</a>

### 7. Prove you are a resident

{% include 'common-content/proving-identity.html' %}

# Apply for an older person's bus pass
