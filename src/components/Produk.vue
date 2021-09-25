<template>
  <main id="content">
    <div class="container-lg">
      <div class="row">
        <!-- filterproduk -->
        <div id="filterproduk" class="col-sm-4 col-md-4 col-lg-3">
          <!-- <div class="card">
              <div class="card-body">
                <form>
                  <fieldset>
                    <legend>Filter Produk</legend>
                    <div class="mb-3">
                      <label for="dropJenjang" class="form-label">Pilih Jenjang :</label>
                      <select id="dropJenjang" class="form-select">
                        <option>-- Pilih Jenjang --</option>
                        <option>SD</option>
                        <option>SMP</option>
                        <option>SMA</option>
                        <option>UMUM</option>
                      </select>
                    </div>
                    <div class="mb-3">
                      <div class="form-check">
                        <input class="form-check-input" type="checkbox" id="checkBerbayar">
                        <label class="form-check-label" for="checkBerbayar">
                          Berbayar
                        </label>
                      </div>
                      <div class="form-check">
                        <input class="form-check-input" type="checkbox" id="checkGratis">
                        <label class="form-check-label" for="checkGratis">
                          Gratis
                        </label>
                      </div>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                  </fieldset>
                </form>
              </div>
            </div> -->

          <div class="accordion" role="tablist">
            <b-card no-body class="mb-1">
              <b-card-header header-tag="header" class="p-1" role="tab">
                <b-button block v-b-toggle.accordion-1 variant="info" >Filter Produk  </b-button>
              </b-card-header>
              <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
                <b-card-body>
                  <form>
                      <fieldset>
                        <legend>Filter Produk</legend>
                        <div class="mb-3">
                          <b-label for="dropJenjang" class="form-label">Pilih Jenjang :</b-label>
                          <select id="dropJenjang" class="form-select">
                            <option>-- Pilih Jenjang --</option>
                            <option>SD</option>
                            <option>SMP</option>
                            <option>SMA</option>
                            <option>UMUM</option>
                          </select>
                        </div>
                        <div class="mb-3">
                          <div class="form-check">
                            <input class="form-check-input" type="checkbox" id="checkBerbayar">
                            <label class="form-check-label" for="checkBerbayar">
                              Berbayar
                            </label>
                          </div>
                          <div class="form-check">
                            <input class="form-check-input" type="checkbox" id="checkGratis">
                            <label class="form-check-label" for="checkGratis">
                              Gratis
                            </label>
                          </div>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                      </fieldset>
                    </form>
                  <b-card-text>{{ text }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>


        </div>
        <!-- /filterproduk -->

        <!-- produk -->
        <div id="produk" class="col-sm-8 col-md-8 col-lg-9">
          <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=1"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=2"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=3"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=4"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=5"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=6"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=15"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=16"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
            <div class="col-6 col-sm-6 col-md-6 col-lg-4 kartu">
              <div class="card h-100">
                <img
                  src="https://picsum.photos/263/152?random=17"
                  class="card-img-top"
                  alt="Alternate Text"
                />
                <div class="card-body">
                  <h5 class="card-title">Try Out UTBK</h5>
                  <p class="card-text">UM-UGM.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Daftar</small>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- /produk -->
      </div>
    </div>
  </main>
</template>
<script>
export default {
  name: "produk"
};
</script>
<style></style>
