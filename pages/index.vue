<template>
    <div classs="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung/tambah">
                    <div class="card bg-pengunjung rounded-5">
                        <div class="card-body">
                            <h2>pengunjung</h2>
                        </div>
                    </div>
                </nuxt-link>
              </div>   

              <div class="col-lg-6">
                <nuxt-link to="/buku">
                    <div class="card bg-buku rounded-5">
                        <div class="card-body">
                            <h2>Cari Buku</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .card {
        height: 250px;
        box-shadow: 1px 1px 10px #ffffff
    }
    .card.bg-pengunjung {
        background-image: url('../asset/img/bg-home-kunjungan.jpeg');
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover;
    }
    .card.bg-buku {
        background: url('../asset/img/bg-home-cari-buku.jpg') no-repeat center center;
        background-size: cover;
    }
</style>