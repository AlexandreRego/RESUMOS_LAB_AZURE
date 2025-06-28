# RESUMOS_LAB_AZURE
Repositorio para observações sobre AZURE

No lab atual, especificamente, tivemos um turn sobre as principais funcionalidades contidas no menu da plataforma alem de dicas de segurança e direcionamentos de aulas futuras.

** Criando uma VM - Treinamento Microsoft Azure: https://learn.microsoft.com/pt-br/training/modules/create-windows-virtual-machine-in-azure/?source=recommendations

Criação de primeiro Banco de Dados no Azure. JSON:

{
    "sku": {
        "name": "GP_Gen5",
        "tier": "GeneralPurpose",
        "family": "Gen5",
        "capacity": 2
    },
    "kind": "v12.0,user,vcore",
    "properties": {
        "collation": "SQL_Latin1_General_CP1_CI_AS",
        "maxSizeBytes": 34359738368,
        "status": "Online",
        "databaseId": "2669e3b0-6174-498a-a606-c38c788fc607",
        "creationDate": "2025-06-28T12:54:28.617Z",
        "currentServiceObjectiveName": "GP_Gen5_2",
        "requestedServiceObjectiveName": "GP_Gen5_2",
        "defaultSecondaryLocation": "southcentralus",
        "catalogCollation": "SQL_Latin1_General_CP1_CI_AS",
        "zoneRedundant": false,
        "licenseType": "LicenseIncluded",
        "maxLogSizeBytes": 193273528320,
        "earliestRestoreDate": "2025-06-28T12:57:31Z",
        "readScale": "Disabled",
        "currentSku": {
            "name": "GP_Gen5",
            "tier": "GeneralPurpose",
            "family": "Gen5",
            "capacity": 2
        },
        "currentBackupStorageRedundancy": "Local",
        "requestedBackupStorageRedundancy": "Local",
        "maintenanceConfigurationId": "/subscriptions/7dc036c7-1a1e-4060-88a8-263d6bdecbab/providers/Microsoft.Maintenance/publicMaintenanceConfigurations/SQL_Default",
        "isLedgerOn": false,
        "isInfraEncryptionEnabled": false,
        "availabilityZone": "NoPreference"
    },
    "location": "brazilsouth",
    "tags": {
        "SQL-db": "SQL"
    },
    "id": "/subscriptions/7dc036c7-1a1e-4060-88a8-263d6bdecbab/resourceGroups/db_sql/providers/Microsoft.Sql/servers/db-sql-teste/databases/teste-db",
    "name": "teste-db",
    "type": "Microsoft.Sql/servers/databases",
    "apiVersion": "2022-11-01-preview"
}
