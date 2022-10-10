<template>

<div>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Create States
                        <router-link :to="{name:'EmployeesIndex'}" class="float-right">Back</router-link>
                    </div>
                    <div class="card-body">
                        <form>

                            <div class="row mb-3">
                                <label for="country_id" class="col-md-4 col-form-label text-md-end">Country</label>
    
                                <div class="col-md-6">
                                    <select name="country_id" id="country_id" class=" form-control" aria-label="Default select example">
                                        <option selected>Open this select menu</option>
                                    </select>
                                </div>
                            </div>
                            
                            <div class="row mb-3">
                                <label for="name" class="col-md-4 col-form-label text-md-end">Name</label>
                                <div class="col-md-6">
                                    <input id="name" type="text" class="form-control" name="name" value="" required  autofocus>
                                </div>
                            </div>                         
                            <div class="row mb-0">
                                <div class="col-md-6 offset-md-4">
                                    <button type="submit" class="btn btn-primary">
                                        Store
                                    </button>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    //name: 'EmployeesCreate'
}
</script>

<style>

</style>