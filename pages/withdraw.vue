<template>
  <div class="main">
    <div class="section section-buttons">
      <div class="container mt-5">
        <Dashboard />
        <div class="row mt-2">
          <div class="col-md-12">
            <h5>WITHDRAW ROBUX</h5>
          </div>
          <div class="col-md-12">
            <div class="card">
              <div class="card-body text-center">
                <div class="row">
                  <div class="col-md-12">
                    <Wizard />
                  </div>
                  <div class="col-md-12 mt-4 mb-4">
                    <button class="btn btn-success btn-round btn-lg" @click="earnHandler">
                      ERRN MORE
                    </button>
                    <button class="btn btn-default btn-round btn-lg">
                      CONTINUE
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-12">
            <h5>WITHDRAW HISTORY</h5>
          </div>
          <div class="col-md-12 mt-4">
            <div class="card">
              <table class="table bg-white">
                <tr>
                  <td>ID</td>
                  <td>Username</td>
                  <td>Amount</td>
                  <td>Date</td>
                  <td>Status</td>
                </tr>
                <tr>
                  <td colspan="5" class="text-center">No data available</td>
                </tr>
              </table>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    earnHandler () {
      this.$router.push('/earn')
    }
  }
}
</script>

<style scoped>
.table td, .table th {
    padding: .75rem;
    vertical-align: top;
    border-top: 0px solid #dee2e6;
}
</style>
