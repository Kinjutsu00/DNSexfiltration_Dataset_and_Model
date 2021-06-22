# DNSexfiltration_Dataset_and_Model
Dataset with regular domain names, directory: Dataset_Good    Size: more or less 18 millions of domain names


Dataset with exfiltrated domain nemes: https://nozzle-data.sdn.unsw.edu.au/dns-exfiltration-dataset/files/ExfiltrationAttackFQDNs.csv  Size: 1.4 millions of domain names


Model: model_Isolation_Forest.pkl , open it with pickle:

    import pickle
    # Load from file
    pkl_filename = "model_Isolation_Forest.pk"
    with open(pkl_filename, 'rb') as file:
       clf = pickle.load(file)
