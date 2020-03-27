<template>
  <div>
    <h2 class="mb-3 md:text-lg text-gray-900 font-medium">
      Travel
    </h2>

    <p class="mb-3">
    </p>

    <div id="svgMap" class="mb-16"></div>
  </div>
</template>

<script>
export default {
  name: 'Map',
  props: {},
  mounted() {
    new svgMap({
      targetElementID: 'svgMap',
      minZoom: 1.1,
      maxZoom: 1.1,
      mouseWheelZoomEnabled: false,
      flagType: 'emoji',
      noDataText: 'Not visited',
      data: {
        data: {
          visits: {
            name: 'Visited'
          }
        },
        applyData: 'visits',
        values: {
          AU: { visits: 'yes' },
          AZ: { visits: 'yes' },
          CY: { visits: 'yes' },
          DE: { visits: 'yes' },
          DK: { visits: 'yes' },
          EE: { visits: 'yes' },
          ES: { visits: 'yes' },
          FI: { visits: 'yes' },
          FR: { visits: 'yes' },
          GB: { visits: 'yes' },
          CN: { visits: 'yes' },
          ID: { visits: 'yes' },
          IS: { visits: 'yes' },
          KR: { visits: 'yes' },
          LT: { visits: 'yes' },
          LV: { visits: 'yes' },
          NL: { visits: 'yes' },
          NO: { visits: 'yes' },
          PT: { visits: 'yes' },
          RU: { visits: 'yes' },
          SE: { visits: 'yes' },
          TN: { visits: 'yes' },
          TR: { visits: 'yes' },
          UA: { visits: 'yes' },
        }
      }
    });
  }
}
</script>

<style lang="postcss">
.svgMap-map-wrapper {
  background: none;
}

.svg-pan-zoom_viewport {
  width: 100%;
}

.svgMap-map-controls-wrapper {
  display: none !important;
}
</style>
