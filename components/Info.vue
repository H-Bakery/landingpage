<template>
  <v-container fluid>
    <v-row dense>
      <v-col cols="12">
        <v-card>
          <v-card-title v-text="'Bestellen'"></v-card-title>
          <v-card-text>
            <p>06841 2229</p>
            <p>01522 6621236</p>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="6">
        <v-card>
          <v-card-title v-text="'Anfahrt'"></v-card-title>
          <v-card-text>
            <p>Eckstraße 3</p>
            <p>66424 Homburg</p>
            <p>Deutschland</p>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="6">
        <v-card>
          <v-card-title v-text="'Öffnungszeiten'"></v-card-title>
          <v-card-text>
            <table itemprop="openingHours">
              <tbody>
                <tr>
                  <th>Mo:</th>
                  <td>
                    <span>05:00–12:00 Uhr,</span>
                    <span>14:00–17:00 Uhr</span>
                  </td>
                </tr>
                <tr>
                  <th>Di:</th>
                  <td>
                    <span>05:00–12:00 Uhr,</span>
                    <span>14:00–17:00 Uhr</span>
                  </td>
                </tr>
                <tr>
                  <th>Mi:</th>
                  <td>
                    <span>Geschlossen</span>
                  </td>
                </tr>
                <tr>
                  <th>Do:</th>
                  <td>
                    <span>05:00–12:00 Uhr,</span>
                    <span>14:00–17:00 Uhr</span>
                  </td>
                </tr>
                <tr>
                  <th>Fr:</th>
                  <td>
                    <span>05:00–12:00 Uhr,</span>
                    <span>14:00–17:00 Uhr</span>
                  </td>
                </tr>
                <tr>
                  <th>Sa:</th>
                  <td>
                    <span>05:00–12:00 Uhr</span>
                  </td>
                </tr>
                <tr>
                  <th>So:</th>
                  <td>
                    <span>Geschlossen</span>
                  </td>
                </tr>
              </tbody>
            </table>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>

<style>
.theme--dark.v-card {
  color: var(--primary);
  background-color: var(--white);
}

.theme--dark.v-card > .v-card__text,
.theme--dark.v-card .v-card__subtitle {
  color: var(--primary);
}
</style>
