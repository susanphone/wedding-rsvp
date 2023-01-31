<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import FlightIcon from './icons/IconFlight.vue'
import HotelIcon from './icons/IconHotel.vue'
import DestinationIcon from './icons/IconDestination.vue'
import InfoIcon from './icons/IconInformation.vue'
import FAQIcon from './icons/IconFAQ.vue'
import HelloWorld from './HelloWorld.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <InfoIcon />
    </template>
    <template #heading>Guest Information</template>
    Please fill out the following form so we know when to 
    expect you.
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <FlightIcon />
    </template>
    <template #heading>Flight Information</template>
    DNV to LHR: UA27 from Denver: June 11 @ 17:30 - London: June 12 @ 9:40
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <HotelIcon />
    </template>
    <template #heading>Hotel Information</template>
    We will staying at
    <a href="https://artistresidence.co.uk/our-hotels/cornwall/" target="_blank" rel="noopener">Artist Residence</a>
    hotel. Don't worry, we are covering your hotel stay. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DestinationIcon />
    </template>
    <template #heading>Destination</template>
    We will be in the town of Penzance from Monday afternoon through Thrusday morning.
    We can check into the hotel after 15:00 and checkout is before 11:00.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <FAQIcon />
    </template>
    <template #heading>Questions</template>
    Please reach out to the bride or groom!
  </WelcomeItem>
</template>
