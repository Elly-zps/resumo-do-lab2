# resumo-do-lab2
Tipos de serviço de nuvem
IaaS, PaaS e SaaS
IaaS (infraestrutura como serviço).
PaaS (plataforma como serviço).
Software como Serviço (SaaS).
Identificar os casos de uso apropriados para cada serviço de nuvem (IaaS, PaaS e SaaS).

____ 
Atualização 
Rrealizei também a criação do Banco de Dados no Azure. 

/subscriptions/fae4c7b4-0b41-48b4-ba47-fc8f10da290d/resourceGroups/AZ-900_Lab_DIO/providers/Microsoft.Sql/servers/felipini/databases/elly_teste
Segue Jason 

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
        "databaseId": "0ec8e804-cf56-425b-9dab-2d6e28f73537",
        "creationDate": "2024-10-23T14:04:52.183Z",
        "currentServiceObjectiveName": "GP_Gen5_2",
        "requestedServiceObjectiveName": "GP_Gen5_2",
        "defaultSecondaryLocation": "centralus",
        "catalogCollation": "SQL_Latin1_General_CP1_CI_AS",
        "zoneRedundant": false,
        "licenseType": "LicenseIncluded",
        "maxLogSizeBytes": 193273528320,
        "earliestRestoreDate": "2024-10-23T14:08:40Z",
        "readScale": "Disabled",
        "currentSku": {
            "name": "GP_Gen5",
            "tier": "GeneralPurpose",
            "family": "Gen5",
            "capacity": 2
        },
        "currentBackupStorageRedundancy": "GeoZone",
        "requestedBackupStorageRedundancy": "GeoZone",
        "maintenanceConfigurationId": "/subscriptions/fae4c7b4-0b41-48b4-ba47-fc8f10da290d/providers/Microsoft.Maintenance/publicMaintenanceConfigurations/SQL_Default",
        "isLedgerOn": false,
        "isInfraEncryptionEnabled": false,
        "availabilityZone": "NoPreference"
    },
    "location": "eastus2",
    "tags": {},
    "id": "/subscriptions/fae4c7b4-0b41-48b4-ba47-fc8f10da290d/resourceGroups/AZ-900_Lab_DIO/providers/Microsoft.Sql/servers/felipini/databases/elly_teste",
    "name": "elly_teste",
    "type": "Microsoft.Sql/servers/databases"
}
