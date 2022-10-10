using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ObjectsUsed : MonoBehaviour
{
  GameObject[] allObjects;
    // Start is called before the first frame update
    void Start()
    {
      allObjects = UnityEngine.GameObject.FindObjectsOfType<GameObject>();
      foreach(GameObject obj in allObjects)
      {
        Debug.Log("Objeto presente en escena con nombre " + obj.name);
      }
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
