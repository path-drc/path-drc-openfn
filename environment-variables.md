## Environment Variables

<table>
  <thead>
    <tr>
      <th>Variable Name</th>
      <th>Description</th>
      <th>Default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>OPENFN_DATABASE_URL</td>
      <td>The URL of the PostgreSQL database</td>
      <td>postgresql://openfn:instant101@postgres-1:5432/lightning_dev</td>
    </tr>
    <tr>
      <td>OPENFN_DISABLE_DB_SSL</td>
      <td>Whether to disable SSL for the database connection</td>
      <td>true</td>
    </tr>
    <tr>
      <td>OPENFN_IS_RESETTABLE_DEMO</td>
      <td>Whether the application is running in resettable demo mode</td>
      <td>true</td>
    </tr>
    <tr>
      <td>OPENFN_LISTEN_ADDRESS</td>
      <td>The IP address to listen on</td>
      <td>0.0.0.0</td>
    </tr>
    <tr>
      <td>OPENFN_LOG_LEVEL</td>
      <td>The log level for the application</td>
      <td>debug</td>
    </tr>
    <tr>
      <td>OPENFN_ORIGINS</td>
      <td>The allowed origins for CORS</td>
      <td>http://localhost:4000</td>
    </tr>
    <tr>
      <td>OPENFN_PRIMARY_ENCRYPTION_KEY</td>
      <td>The primary encryption key</td>
      <td>KLu/IoZuaf+baDECd8wG4Z6auwNe6VAmwh9N8lWdJ1A=</td>
    </tr>
    <tr>
      <td>OPENFN_SECRET_KEY_BASE</td>
      <td>The secret key base</td>
      <td>jGDxZj2O+Qzegm5wcZ940RfWO4D6RyU8thNCr5BUpHNwa7UNV52M1/Sn+7RxiP+f</td>
    </tr>
    <tr>
      <td>OPENFN_WORKER_RUNS_PRIVATE_KEY</td>
      <td>The private key for worker runs</td>
      <td>LS0tLS1CRUdJTiBQUklWQVRFIEtFWS0tLS0tCk1JSUV2Z0lCQURBTkJna3Foa2lHOXcwQkFRRUZBQVNDQktnd2dnU2tBZ0VBQW9JQkFRREVtR3drUW5pT0hqVCsKMnkyRHFvRUhyT3dLZFI2RW9RWG9DeDE4MytXZ3hNcGthTFZyOFViYVVVQWNISGgzUFp2Z2UwcEIzTWlCWWR5Kwp1ajM1am5uK2JIdk9OZGRldWxOUUdpczdrVFFHRU1nTSs0Njhldm5RS0h6R29DRUhabDlZV0s0MUd5SEZCZXppCnJiOGx2T1A1NEtSTS90aE5pVGtHaUIvTGFLMldLcTh0VmtoSHBvaFE3OGIyR21vNzNmcWtuSGZNWnc0ZE43d1MKdldOamZIN3QwSmhUdW9mTXludUxSWmdFYUhmTDlnbytzZ0thc0ZUTmVvdEZIQkYxQTJjUDJCakwzaUxad0hmdQozTzEwZzg0aGZlTzJqTWlsZlladHNDdmxDTE1EZWNrdFJGWFl6V0dWc25FcFNiOStjcWJWUXRvdEU4QklON09GClRmaEx2MG9uQWdNQkFBRUNnZ0VBV3dmZyt5RTBSVXBEYThiOVdqdzNKdUN4STE1NzFSbmliRUhKVTZzdzNyS0EKck9HM0w5WTI0cHhBdlVPSm5GMFFzbThrUVQ4RU1MU3B6RDdjdDVON2RZMngvaGY4TThhL0VSWXM4cFlYcXI5Vwpnbnh3NldGZ0R6elFHZ0RIaW0raXNudk5ucFdEbTRGVTRObG02d2g5MzVSZlA2KzVaSjJucEJpZjhFWDJLdE9rCklOSHRVbFcwNFlXeDEwS0pIWWhYNFlydXVjL3MraXBORzBCSDZEdlJaQzQxSWw0N1luaTg1OERaL0FaeVNZN1kKWTlTamNKQ0QvUHBENTlNQjlSanJDQjhweDBjWGlsVXBVZUJSYndGalVwbWZuVmhIa1hiYlM1U0hXWWM4K3pLRQp2ajFqSEpxc2UyR0hxK2lHL1V3NTZvcHNyM2x3dHBRUXpVcEJGblhMMFFLQmdRRDM5bkV3L1NNVGhCallSd1JGCkY2a2xOYmltU2RGOVozQlZleXhrT0dUeU5NSCtYckhsQjFpOXBRRHdtMit3V2RvcWg1ZFRFbEU5K1crZ0FhN0YKbXlWc2xPTW4wdnZ2cXY2Wkp5SDRtNTVKU0lWSzBzRjRQOTRMYkpNSStHUW5VNnRha3Y0V0FSMkpXaURabGxPdAp3R01EQWZqRVIrSEFZeUJDKzNDL25MNHF5d0tCZ1FESzk3NERtV0c4VDMzNHBiUFVEYnpDbG9oTlQ2UldxMXVwCmJSWng4ZGpzZU0vQ09kZnBUcmJuMnk5dVc3Q1pBNFVPQ2s4REcxZ3ZENVVDYlpEUVdMaUp5RzZGdG5OdGgvaU8KT1dJM0UyczZOS0VMMU1NVzh5QWZwNzV4Ung5cnNaQzI2UEtqQ0pWL2lTVjcyNlQ1ZTFzRG5sZUtBb0JFZnlDRgpvbEhhMmhybWxRS0JnUURHT1YyOWd1K1NmMng1SVRTWm8xT1ZxbitGZDhlZno1d3V5YnZ3Rm1Fa2V1YUdXZDh1CnJ4UFM3MkJ6K0Y1dUJUWngvMWtLa0w4Zm94TUlQN0FleW1zOWhUeWVybnkyMk9TVlBJSmN3dExqMUxTeDN3L0kKK0kyaVpsYVl1akVlZXpXbHY1S2R0cUNORjk3Zzh0ck1NTnMySVZKa1h1NXFwUk82V0ZXRzZGL2h4d0tCZ0hnNApHYUpFSFhIT204ekZTU2lYSW5FWGZKQmVWZmJIOUxqNzFrbVRlR3RJZTdhTlVHZnVxY1BYUGRiZUZGSHRsY2ZsCkx6dWwzS3V6VFExdEhGTnIyWkl5MTlQM1o1TSs4R2c5Y1FFeVRWYmlpV2xha2x0cmttRnRtQTI4bE0zVEZPWmkKUUNWMUZpZStjaWRVeC9qRnFma1F0c1VXQ2llSUxSazZOY1d0WGpXcEFvR0JBTGN6Y210VGlUUEFvWnk0MFV1QQpTOXpUd3RsamhmUWJEVTVjb21EcnlKcnFRU0VOdmQ2VW5HdW0zYVNnNk13dDc0NGxidDAyMC9mSGI0WTJkTGhMCmx4YWJ5b1dQUElRRUpLL1NNOGtURFEvYTRyME5tZzhuV3h5bGFLcHQ5WUhmZ2NYMkYzSzUrc0VSUGNFcVZlWFMKdWZkYXdYQVlFampZK3V2UHZ2YzU3RU1aCi0tLS0tRU5EIFBSSVZBVEUgS0VZLS0tLS0K</td>
    </tr>
    <tr>
      <td>OPENFN_WORKER_SECRET</td>
      <td>The secret key for the worker</td>
      <td>secret_here</td>
    </tr>
    <tr>
      <td>POSTGRES_USER</td>
      <td>The username for the PostgreSQL database</td>
      <td>postgres</td>
    </tr>
    <tr>
      <td>POSTGRES_SERVICE</td>
      <td>The service name for the PostgreSQL database</td>
      <td>postgres-1</td>
    </tr>
    <tr>
      <td>POSTGRES_DATABASE</td>
      <td>The name of the PostgreSQL database</td>
      <td>postgres</td>
    </tr>
    <tr>
      <td>POSTGRES_PASSWORD</td>
      <td>The password for the PostgreSQL database</td>
      <td>instant101</td>
    </tr>
    <tr>
      <td>POSTGRES_PORT</td>
      <td>The port number for the PostgreSQL database</td>
      <td>5432</td>
    </tr>
    <tr>
      <td>OPENFN_POSTGRESQL_DB</td>
      <td>The name of the OpenFn PostgreSQL database</td>
      <td>lightning_dev</td>
    </tr>
    <tr>
      <td>OPENFN_POSTGRESQL_USERNAME</td>
      <td>The username for the OpenFn PostgreSQL database</td>
      <td>openfn</td>
    </tr>
    <tr>
      <td>OPENFN_POSTGRESQL_PASSWORD</td>
      <td>The password for the OpenFn PostgreSQL database</td>
      <td>instant101</td>
    </tr>
    <tr>
      <td>OPENFN_WORKER_LIGHTNING_PUBLIC_KEY</td>
      <td>The public key for the worker lightning</td>
      <td>LS0tLS1CRUdJTiBQVUJMSUMgS0VZLS0tLS0KTUlJQklqQU5CZ2txaGtpRzl3MEJBUUVGQUFPQ0FROEFNSUlCQ2dLQ0FRRUF4SmhzSkVKNGpoNDAvdHN0ZzZxQgpCNnpzQ25VZWhLRUY2QXNkZk4vbG9NVEtaR2kxYS9GRzJsRkFIQng0ZHoyYjRIdEtRZHpJZ1dIY3ZybzkrWTU1Ci9teDd6alhYWHJwVFVCb3JPNUUwQmhESURQdU92SHI1MENoOHhxQWhCMlpmV0ZpdU5Sc2h4UVhzNHEyL0piemoKK2VDa1RQN1lUWWs1Qm9nZnkyaXRsaXF2TFZaSVI2YUlVTy9HOWhwcU85MzZwSngzekdjT0hUZThFcjFqWTN4Kwo3ZENZVTdxSHpNcDdpMFdZQkdoM3kvWUtQcklDbXJCVXpYcUxSUndSZFFObkQ5Z1l5OTRpMmNCMzd0enRkSVBPCklYM2p0b3pJcFgyR2JiQXI1UWl6QTNuSkxVUlYyTTFobGJKeEtVbS9mbkttMVVMYUxSUEFTRGV6aFUzNFM3OUsKSndJREFRQUIKLS0tLS1FTkQgUFVCTElDIEtFWS0tLS0tCg</td>
    </tr>
    <tr>
      <td>OPENFN_IMAGE</td>
      <td>The image name for OpenFn</td>
      <td>openfn/lightning:v2.9.5</td>
    </tr>
    <tr>
      <td>OPENFN_WORKER_IMAGE</td>
      <td>The image name for OpenFn worker</td>
      <td>openfn/ws-worker:latest</td>
    </tr>
    <tr>
      <td>OPENFN_KAFKA_TRIGGERS_ENABLED</td>
      <td>Whether Kafka triggers are enabled</td>
      <td>true</td>
    </tr>
    <tr>
      <td>OPENFN_API_KEY</td>
      <td>The API key for OpenFn</td>
      <td>apiKey</td>
    </tr>
    <tr>
      <td>OPENFN_ENDPOINT</td>
      <td>The endpoint for OpenFn</td>
      <td>http://localhost:4000</td>
    </tr>
    <tr>
      <td>OPENFN_DOCKER_WEB_CPUS</td>
      <td>The number of CPUs allocated to the web container</td>
      <td>2</td>
    </tr>
    <tr>
      <td>OPENFN_DOCKER_WEB_MEMORY</td>
      <td>The amount of memory allocated to the web container</td>
      <td>4G</td>
    </tr>
    <tr>
      <td>OPENFN_DOCKER_WORKER_CPUS</td>
      <td>The number of CPUs allocated to the worker container</td>
      <td>2</td>
    </tr>
    <tr>
      <td>OPENFN_DOCKER_WORKER_MEMORY</td>
      <td>The amount of memory allocated to the worker container</td>
      <td>4G</td>
    </tr>
    <tr>
      <td>FHIR_SERVER_BASE_URL</td>
      <td>The base URL for the FHIR server</td>
      <td>http://openhim-core:5001</td>
    </tr>
    <tr>
      <td>FHIR_SERVER_USERNAME</td>
      <td>The username for the FHIR server</td>
      <td>openfn_client</td>
    </tr>
    <tr>
      <td>FHIR_SERVER_PASSWORD</td>
      <td>The password for the FHIR server</td>
      <td>openfn_client_password</td>
    </tr>
    <tr>
      <td>PGDATA_PATH</td>
      <td>Optional: Host path to use as a bind mount for the Postgres data directory. If not set, a named Docker volume ('pgdata') is used by default.</td>
      <td></td>
    </tr>
  </tbody>
</table>