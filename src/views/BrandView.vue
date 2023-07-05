<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>
<template>
    <!-- Content Header (Page header) -->
    <div class="content-header">
        <div class="container-fluid">
            <div class="row mb-2">
                <div class="col-sm-6">
                    <h1 class="m-0">Brand View</h1>
                </div><!-- /.col -->
                <div class="col-sm-6">
                    <ol class="breadcrumb float-sm-right">
                        <RouterLink to="/" class="breadcrumb-item">
                            Home
                        </RouterLink>
                        <RouterLink to="/brand" class="breadcrumb-item active">
                            Brand
                        </RouterLink>
                    </ol>
                </div><!-- /.col -->
            </div><!-- /.row -->
        </div><!-- /.container-fluid -->
    </div>
    <!-- /.content-header -->

    <!-- Main content -->
    <section class="content">
        <div class="container-fluid">
            <!-- Info boxes -->
            <div class="row">

            </div>
        </div><!--/. container-fluid -->
    </section>
    <!-- /.content -->
</template>