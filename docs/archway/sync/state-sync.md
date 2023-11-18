---
sidebar_position: 2
description: State Sync
---

# State Sync

> State Sync allows new nodes to join a blockchain network by downloading a recent snapshot of the application state instead of processing all historical blocks. This approach is typically faster and requires less data, as the application state is usually more concise than the entire block history.

import SelectPaste from '@site/src/components/SelectPaste';

import { stateSync }  from '@site/src/components/SelectPaste/stateSync.ts';

export let endpoints = [
	    'https://rpc-archway.imperator.co',
];

export let home = 'archway';

export let binary = 'archwayd';

<SelectPaste endpoints={endpoints} codeTemplate={stateSync} home={home} binary={binary} tip="Click on any RPC to paste it into the code block." />