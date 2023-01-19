export default {
    data() {
      return {
        <!-- checkedNames: [] -->
        flyOut: []
      }
    }
  }

<template>
    <!-- <div class="form">
      <h1>Please provide the following information</h1>
    </div>
    <div>Flight Date: {{ flyOut }}</div>

<input type="radio" id="sat" value="sat" v-model="flyOut">
<label for="sat"> Saturday June 10th</label>
<br>
<input type="radio" id="sun" value="sun" v-model="flyOut">
<label for="sun"> Sunday June 11th (The day the bride and groom fly out)</label>
<br>
<input type="radio" id="mon" value="mon" v-model="flyOut">
<label for="mon"> Monday June 12th</label>
<br>
  <div class="form">
        <div>Contact Information:</div>
        
    </div> -->
<div></div>
<div class="form">
  <p>Guest Name {{ guestName }}</p>
  <input v-model="guestName" plaeholder="Paul Bunyon" />
  <p>Phone Number {{ message }}</p>
  <input v-model="message" placeholder="(xxx)-xxx-xxxx" />
</div> 
<div></div>
<div>
<p>What day are you heading to London? {{ selected }}</p>

<select v-model="selected">
  <option disabled value="">Please select one</option>
  <option>Saturday June 10th</option>
  <option>Sunday June 11th</option>
  <option>Monday June 12th</option>
</select>
</div>

<div></div>
<div>
  <div>Are you bringing a plus one: {{ plusone }}</div>
  <input type="radio" id="one" value="One" v-model="plusone" />
  <label for="one">Yes</label>

  <input type="radio" id="two" value="Two" v-model="plusone" />
  <label for="two">No</label>
</div>
<div></div>
<div class="form">
  <p>If yes, who is you guest? {{ plusOne }}</p>
  <input v-model="plusOne" placeholder="Paula Bunyon"/>
</div>

<div></div>
<div class="form">
  <p>Are there any food allergies in your party</p>
  <input type="radio" id="one" value="One" v-model="allergy" />
  <label for="one">Yes</label>

  <input type="radio" id="two" value="Two" v-model="allergy" />
  <label for="two">No</label>

  <p>If yes, please specify {{ food }}</p>
  <input v-model="food" placeholder="Food Allergies" />

</div>
</template>


  
  <style>
  @media (min-width: 1024px) {
    .about {
      min-height: 150vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  