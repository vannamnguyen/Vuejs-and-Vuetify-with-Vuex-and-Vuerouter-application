<template>
	<v-container background-color="grey" class="mt-5 ml-5" fluid>
		<v-row align="center" justify="center">
			<v-col cols="3">
				<v-card class="mx-auto" elevation="2">
					<v-container fluid>
						<v-row>
							<v-col cols="4" md="6" justify="center" align="center">
								<v-card color="pink lighten-1" class="card-icon" dark>
									<v-icon large>mdi-movie-filter-outline</v-icon>
								</v-card>
							</v-col>
							<v-col cols="6" md="6" justify="end" align="end" class="pt-0">
								<p class="font-weight-light grey--text body-2">Number of Rented Movies</p>
								<h1 class="font-weight-light pink--text">15</h1>
							</v-col>
						</v-row>
						<v-divider></v-divider>
						<v-row>
							<v-col class="pb-0">
								<v-icon small>mdi-filmstrip</v-icon>
								<span class="font-weight-light body-2 grey--text ml-2">Just Updated</span>
							</v-col>
						</v-row>
					</v-container>
				</v-card>
			</v-col>

			<v-col cols="3">
				<v-card class="mx-auto" elevation="2">
					<v-container fluid>
						<v-row>
							<v-col cols="4" md="6" justify="center" align="center">
								<v-card color="green darken-1" class="card-icon" dark>
									<v-icon large>mdi-account-group-outline</v-icon>
								</v-card>
							</v-col>
							<v-col cols="6" md="6" justify="end" align="end" class="pt-0">
								<p class="font-weight-light grey--text body-2">List of Clients</p>
								<h1 class="font-weight-light green--text">10</h1>
							</v-col>
						</v-row>
						<v-divider></v-divider>
						<v-row>
							<v-col class="pb-0">
								<v-icon small>mdi-account-group-outline</v-icon>
								<span class="font-weight-light body-2 grey--text ml-2">Just Updated</span>
							</v-col>
						</v-row>
					</v-container>
				</v-card>
			</v-col>

			<v-col cols="3">
				<v-card class="mx-auto" elevation="2">
					<v-container fluid>
						<v-row>
							<v-col cols="4" md="6" justify="center" align="center">
								<v-card color="cyan lighten-1" class="card-icon" dark>
									<v-icon large>mdi-purse-outline</v-icon>
								</v-card>
							</v-col>
							<v-col cols="6" md="6" justify="end" align="end" class="pt-0">
								<p class="font-weight-light grey--text body-2">Inventory</p>
								<h1 class="font-weight-light cyan--text">124</h1>
							</v-col>
						</v-row>
						<v-divider></v-divider>
						<v-row>
							<v-col class="pb-0">
								<v-icon small>mdi-purse-outline</v-icon>
								<span class="font-weight-light body-2 grey--text ml-2">Just Updated</span>
							</v-col>
						</v-row>
					</v-container>
				</v-card>
			</v-col>

			<v-col cols="3">
				<v-card class="mx-auto" elevation="2">
					<v-container fluid>
						<v-row>
							<v-col cols="4" md="6" justify="center" align="center">
								<v-card color="warning lighten-1" class="card-icon" dark>
									<v-icon large>mdi-cube-scan</v-icon>
								</v-card>
							</v-col>
							<v-col cols="6" md="6" justify="end" align="end" class="pt-0">
								<p class="font-weight-light grey--text body-2">List of No Stock</p>
								<h1 class="font-weight-light warning--text">5</h1>
							</v-col>
						</v-row>
						<v-divider></v-divider>
						<v-row>
							<v-col class="pb-0">
								<v-icon small>mdi-cube-scan</v-icon>
								<span class="font-weight-light body-2 grey--text ml-2">Just Updated</span>
							</v-col>
						</v-row>
					</v-container>
				</v-card>
			</v-col>
		</v-row>
	</v-container>
</template>

<script>
export default {
	name: "AdminDashboard",
};
</script>

<style scoped>
.card-icon {
	margin-top: -40px;
	padding-top: 35px;
	padding-bottom: 35px;
}
</style>