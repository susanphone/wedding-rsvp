import Vue from 'vue'
import Buefy from 'buefy'
import 'buefy/dist/buefy.css'

Vue.use(Buefy)

<h1>Main Page</h1>
<div class="tile is-ancestor">
    <div class="tile is-vertical is-8">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification is-primary">
            <p class="title">Wedding Date</p>
            <p class="subtitle">June 14th, 2023 @ 4:00pm</p>
          </article>
          <article class="tile is-child notification is-warning">
            <p class="title">Hotel</p>
            <p class="subtitle">Artist Residence </p>
            <p class="content">Check-in is at 3:00pm, check-out is at 11:00am</p>
          </article>
        </div>

        <div class="tile is-parent">
          <article class="tile is-child notification is-info">
            <p class="title">Venue</p>
            <p class="subtitle">Tremenherre Sculture Gardens</p>
            <figure class="image is-4by3">
              <img src="https://www.tremenheere.co.uk/wp-content/uploads/2019/05/pagoda-garden-outdoor-wedding-venue-cornwall-tremenheere-sculpture-gardens-1.jpg">
            </figure>
          </article>
        </div>
      </div>

      <div class="tile is-parent">
        <article class="tile is-child notification is-danger">
          <p class="title">Trip Itinerary</p>
          <p class="subtitle">Monday</p>
          <p class="content">Hotel checkin at 3pm</p>
          <p class="subtitle">Tuesday</p>
          <p class="content">St. Michaels Mount</p>
          <p class="content">Rehearsal Dinner</p>
          <p class="subtitle">Wednesdau</p>
          <p class="content">Wedding at 4pm</p>
          <p class="content">Dinner at 6pm</p>
          <p class="subtitle">Thursday</p>
          <p class="content">Checkout by 11am</p>
          <figure class="image is-4by3">
            <img src="wedding-rsvp/src/assets/spokane.jpg">
            </figure>
         
        </article>
      </div>
    </div>

    <div class="tile is-parent">
      <article class="tile is-child notification is-success">
        <div class="content">
          <p class="title">Things to do in Penzance</p>
          <p class="subtitle">TODO</p>
         
          </div>
        </div>
      </article>
    </div>
  </div>