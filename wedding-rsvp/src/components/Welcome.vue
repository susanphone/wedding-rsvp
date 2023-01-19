<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import FlightIcon from './icons/IconFlight.vue'
import HotelIcon from './icons/IconHotel.vue'
import DestinationIcon from './icons/IconDestination.vue'
import InfoIcon from './icons/IconInformation.vue'
import FAQIcon from './icons/IconFAQ.vue'
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
    DNV to LHR: UA27 from Denver 5:30pm - London: 9:40am
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <HotelIcon />
    </template>
    <template #heading>Hotel Information</template>
    We will staying at
    <a href="https://artistresidence.co.uk/our-hotels/cornwall/" target="_blank" rel="noopener">Artist Residence</a>
    hotel
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DestinationIcon />
    </template>
    <template #heading>Destination</template>
    We will be in the town of Penzance from Monday afternoon through Thrusday morning. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <FAQIcon />
    </template>
    <template #heading>Questions</template>
    Please reach out to the bride or groom!
  </WelcomeItem>
</template>
