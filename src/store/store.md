we are creating this store folder to store the database fetched from mongoDB to create cache memory so that if a previous data is feed again then we can fetch previous one values

using reducer we can create a central store  so if using fetch u get the data inside reducer(state) then we can access the data anywhere inside our react app but for that we have to manually update the data or refresh it so to solve that problem we use RTK query

RtK query will automatically update the data if there is a change in the backend


