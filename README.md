# Firebase Key Signing Party

The Firebase crew just upgraded offices and we're overloading the office warming party with a key signing party!

## Time & Place

→ Thursday, April 3 at 7:00pm - 10:30pm in PDT @  [22 4th Street, 10th Floor, San Francisco, CA](https://www.google.com/maps/search/22+4th+Street,+10th+Floor,+San+Francisco,+CA/@37.767997,-122.3921315,14z)

## Key Signing Details

We'll be holding a ["List Based" key party](http://cryptnet.net/fdp/crypto/keysigning_party/en/keysigning_party.html#list_based). In a nutshell this in-person event will serve to expand the public key "web of trust." It'll allow those that attend to verify the fingerprints of each others' public keys without relying on an untrusted communication medium (i.e. verification of fingerprints takes place face to face.)


## What we need from you

### Before the party

0. Send a pull request to this repo and add your ascii armored public key to pubkeys/ 
0. (Optional, but strongly recommended) The day before the event: make a printout of the keyring (available in this repo the day before the event) that has the list of keys, key owner details (name, email), and the key fingerprints.


### During the party

0. Bring a government issued form of identification that matches details listed on your key to the event.
0. Bring your own key fingerprint: `gpg --list-secret-keys --fingerprint` Others will be asking you to corroborate fingerprints.
0. Check others' identifactions and fingerprints based on the keyring of those attending. (Keyring of attendees will be available in this repo the day before the event.)


### After the party

0. Sign the keys that you verified at the in-person event.
0. Send the signed keys to a public key server `gpg --keyserver pgp.mit.edu --send-key $KEYID`


# 🔥
