# Intellectual Property Licence (Australia)

### Purpose

The language in this repo licenses intellectual property rights in **Australian** legal agreements.

### Simple Licences with LawPatch

Licensing intellectual property is a technical area.  If you want to draft a licence and make its characteristics clear, you end up with a lot of formulaic language. Lawpatch licences allow you to cut this clutter out of your contracts.

There are two Lawpatch intellectual property licence positions: expansive and restrictive. Instructions on how to use them are below.

### Expansive licence

The expansive licence creates a starting point that is good for the person **receiving** the licence. The parties can then customise add restrictions explicitly, to shift the balance back toward the person giving the licence. If they do not add any restrictions, then the most expansive characteristics automatically apply.

The example below assumes the use of the LawPatch clause <a href="https://github.com/lawpatch/lawpatch-docs" target="_blank">here</a>.

If you want your license to be irrevocable, perpetual, transferable, sub-licensable, non-exclusive, royalty free and global, you just need to write:

> Provider grants an <a href="https://github.com/lawpatch/au-ip_license/blob/5a7f77c72443475d8d34fc0487547dfac0671287/au-license_ip.md" target="_blank">expansive licence</a> to the Customer in relation to the Code for any purpose.

If you want your licence to be **non-transferable**, **exclusive** and applicable **only in Australia** (but expansive in every other way), you just need to write:

> Provider grants an exclusive, non-transferable <a href="https://github.com/lawpatch/au-ip_license/blob/5a7f77c72443475d8d34fc0487547dfac0671287/au-license_ip.md" target="_blank"> expansive licence</a> to the Customer to deal with the Code in Australia for any purpose.

### Restrictive licence

The starting point of this licence is good for the person **giving** the licence. The parties can then add expansions to shift the balance more towards the person receiving it. If they do not add any expansions, the restrictive arrangements automatically apply.

If you want your licence to be revocable, non-transferrable and un-sublicensensable, you just need to write:

> Provider grants a [restrictive licence](http://github/lawpatch/link) to the Customer to deal with the Code in Australia for any purpose.

If you want your licence to be irrevocable, but otherwise restrictive, you just need to write:

> Provider grants an irrevocable [restrictive licence](http://github/lawpatch/link) to the Customer to deal with the Code in Australia for any purpose.

### Position parameters

The language in this repos is *not* language that you can import wholesale with a simple incorporation by reference. It assumes that you have included certain information in the importing clause. It also allows for certain **optional** information to be included in the clause.

**au-license_ip_expansive.md**

The compulsory parameters for this patch are:

- `Licensor` - The party licensing the intellectual property;
- `Licensee` - The party receiving the licence of the intellectual property; and
- `Subject` - The intellectual property that is licensed (the more specific the description the better).

The optional parameters for this patch are:

- `Purpose` - the purpose that the Licensor will allow the subject intellectual property to be used for.
- `Restrictions` - one or many of the following can be used:
    - revocable;
    - limited term;
    - non-transferrable;
    - non-sublicensable;
    - exclusive;
    - royalties due; and
    - confined to a territory.
- `Exception` - An exception to the licence.
- `Terms and conditions` (optional) - Any terms and conditions that apply to the licence. The Provision does not need to contain all the terms and conditions. It may say that the licence is subject to the terms and conditions in the whole Agreement.

**au-license_ip_restrictive.md**

The compulsory parameters are:

- `Licensor` - The party licensing the intellectual property;
- `Licensee` - The party receiving the licence of the intellectual property;
- `Subject` - The intellectual property that is licensed (the more specific the description the better);
- `Purpose` - the purpose that the Licensor will allow the subject intellectual property to be used for;
- `Duration` - The length of time for which the licence is granted (it may be forever - 'perpetual'- or for a specified period); and
- `Territory` - The place in which the licence applies (it may be everywhere - 'global' - or in a specified region, country, state or city).

The optional parameters are:

- `Expansions` - one or many of the following can be used:
    - irrevocable;
    - transferrable
    - sub-licensable; and
    - exclusive.
- `Exception` - An exception to the licence.
- `Royalties` - Whether any royalty payments are due. The licence may be royalty free, or it may specify royalty arrangements and amounts. If you do not say that royalties apply, or that the licence is royalty free, then whether royalties apply will just depend on the law and the IP that is licensed.
- `Terms and conditions` - Any terms and conditions that apply to the licence. The Provision does not need to contain all the terms and conditions. It may say that the licence is subject to the terms and conditions in the whole Agreement.

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the language is well aligned with your circumstances.

### Licence

The language in this repo is released under the license in `license.md`.
