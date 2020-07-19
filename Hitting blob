from azure.storage.blob import BlobClient

blob = BlobClient(account_url="https://storage-account_name.blob.core.windows.net",
                  container_name="example",
                  blob_name="file.txt",
                  credential="your shared access key")
data = blob.download_blob()

#with open("example.txt", "wb") as f:
#    data = blob.download_blob()
#    data.readinto(f)
